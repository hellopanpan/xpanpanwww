<template>
  <div class="bg1">
    <div class="move-wrap" ref='movebg' @mousedown="move">
      <Index-item></Index-item>
    </div>
  </div>
</template>

<script>
  import IndexItem from '@/components/IndexItem'
  export default {
    name:'',
    props:[''],
    components: {
      IndexItem
    },
    data () {
      return {
        left: 0
      };
    },
    mounted() {
      // this.$refs.movebg.style.transform = 'translate(600px, 0px)';
    },
    methods: {
      move(e){
        let odiv = e.target;    //获取目标元素
        let that = this;
        let left = 0
        //算出鼠标相对元素的位置
        let disX = e.clientX;
        // let disY = e.clientY - odiv.offsetTop;
        document.onmousemove = (e)=>{    //鼠标按下并移动的事件
          //用鼠标的位置减去鼠标相对元素的位置，得到元素的位置
          left = e.clientX - disX;  
          // let top = e.clientY - disY;
          //绑定元素位置到positionX和positionY上面
          // this.positionX = top;
          // this.positionY = left;
          //移动当前元素
          if (this.left + left < 0 && this.left + left > -2600) {
            that.$refs.movebg.style.transform = `translate(${this.left + left}px, 0px)`;
          }
        };
        document.onmouseup = () => {
          if (this.left + left < 0 && this.left + left > -2600) {
            this.left = this.left + left;
          }
          document.onmousemove = null;
          document.onmouseup = null;
        };
      } 
    } 
  }

</script>
<style lang='less' scoped>
  .bg1{
    width: 100%;
    height: 100%;
    background: url('~@/assets/images/bg1.jpg') no-repeat;
    background-size: cover;
    overflow: hidden;
    .move-wrap{
      transform: translate(0px, 0px);
      transition: 0.2s;
    }
  }
</style>