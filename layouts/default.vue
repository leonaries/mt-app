<template>
  <el-container>
    <el-header>
      <my-header/>
    </el-header>
    <el-main>
        <nuxt/>
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script>
  const  Myheader  = require ('@/components/public/header/index.vue')
  export default {
    name:'default',
    components:{
      Myheader:Myheader
    }
  }
</script>

