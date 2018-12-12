<template>
    <div class="m-header">
      <el-row>
        <el-col>
          <topBar/>
        </el-col>
      </el-row>
      <el-row>
        <el-col>
          <searchBar/>
        </el-col>
      </el-row>
    </div>
</template>

<script>
  import topBar from './topbar'
  import searchBar from './searchbar'
    export default {
        name: "index",
        components:{
          topBar,
          searchBar
        }
    }
</script>

<style scoped lang="scss">
  @import "@/assets/css/public/header/index.scss";
</style>
