<template>
  <el-row :gutter="15" class="m-header">
    <el-col :span="6">
      <geo/>
    </el-col>
    <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
    <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
  </el-row>

</template>

<script>
  const  Geo = require ("./geo.vue")
    export default {
        name: "index",
        components:{
          Geo
        }
    }
</script>

<style scoped lang="scss">
  /*@import "@/assets/css/public/layout.scss";*/
</style>
