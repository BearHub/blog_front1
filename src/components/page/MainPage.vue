<template>
    <el-row :gutter="10">
        <el-col :xs="8" :sm="6" :md="4" :lg="3" :xl="4"><div class="grid-content bg-touming"></div></el-col>
        <el-col :xs="4" :sm="6" :md="8" :lg="9" :xl="12">
            <div class="grid-content bg-purple-light">
                <!-- 全部博文 -->
                <Articles/>
            </div>
        </el-col>
        <el-col :xs="4" :sm="6" :md="8" :lg="9" :xl="4">
          <div class="grid-content bg-purple-light">
            <Category/>
          </div>
        </el-col>
        <el-col :xs="8" :sm="6" :md="4" :lg="3" :xl="4"><div class="grid-content bg-touming"></div></el-col>
    </el-row>
</template>

<script>
import Articles from '../compoent/article'
import Category from '../compoent/category'

export default {
  name: 'MainPage',
  components: {
    Articles,
    Category
  }
}
</script>

<style scoped>
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-touming {
    background: rgba(0,0,0,0);
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #ffffff;
    padding-top: 20px;
    padding-bottom: 40px;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
  }
</style>
