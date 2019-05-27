<template>
  <Index-item></Index-item>
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
      
    } 
  }

</script>
<style lang='less' scoped>
  
</style>