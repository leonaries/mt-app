<template>
    <div class="page-index">
        <el-row>
          <el-col :span="5">
            <emenu/>
          </el-col>
          <el-col :span="19">
            <life/>
          </el-col>
        </el-row>
      <el-row>
        3
      </el-row>
    </div>
</template>

<script>
  import Emenu from  '@/components/index/menu'
  import Life  from '@/components/index/life'
export default {
  components: {
    Emenu,
    Life
  }
}
</script>

<style lang="scss">
  @import "@/assets/css/index/index.scss";
  .page-index{
    width: 1190px;
    margin: 0 auto;
  }
</style>
