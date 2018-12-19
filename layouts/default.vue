<template>
  <el-container>
    <el-header>
      <my-header/>
    </el-header>
    <el-main>
        <nuxt/>
    </el-main>
    <el-footer height="100%">
      <my-footer/>
    </el-footer>
  </el-container>
</template>

<script>
  import  Myheader  from  '@/components/public/header/index.vue'
  import  Myfooter  from  '@/components/public/footer/index.vue'
  export default {
    name:'default',
    components:{
      myHeader:Myheader,
      myFooter:Myfooter
    }
  }
</script>
<style>
  .el-header{
    height: auto!important;
  }
</style>

