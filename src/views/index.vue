<template>
  <div class="bg1">
    <Index-item></Index-item>
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

      };
    },

  }

</script>
<style lang='less' scoped>
  .bg1{
    width: 100%;
    height: 100%;
    background: url('~@/assets/images/bg1.jpg') no-repeat;
    background-size: cover;
    overflow: hidden;
  }
</style>