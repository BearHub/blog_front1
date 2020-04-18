<template>
    <el-menu
    :default-active="activeIndex2"
    class="el-menu-demo"
    mode="horizontal"
    @select="handleSelect"
    text-color="#fff"
    active-text-color="#ffd04b">
      <el-row :gutter="20">
        <el-col class="grid-content" :span="2"><span class="logo" style="margin-left:15px"><a to="/"><strong>Bear's Blog</strong></a></span></el-col>
        <el-col :span="19">
          <el-link class="alink" href="">首页</el-link>
          <el-link class="alink" href="">归档</el-link>
          <el-link class="alink" href="">关于</el-link>
          <el-link class="alink" href="">留言</el-link>
          <el-link class="alink" href="">日记</el-link>
          <el-link class="alink" href="">友链</el-link>
        </el-col>
        <el-col :span="3"><el-link underline="false" class="alink" style="float:right;margin: 0 20px 0 0;" href="#">登录</el-link></el-col>
      </el-row>
    </el-menu>
</template>
<script>
export default {
  name: 'navBar',
  data () {
    return {
      activeIndex: '1',
      activeIndex2: '1'
    }
  },
  methods: {
    handleSelect (key, keyPath) {
      console.log(key, keyPath)
    }
  }
}
</script>

<style scoped>
  .el-row {
    height: 55px;
    line-height: 55px;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .logo {
    font-family: barHand;
    color: #686967;
    text-decoration: none;
    font-size: 36px;
  }
  .alink {
    padding-top: 1px;
    display: inline-block;
    width: 70px;
    height: 54px;
    font-size: 16px;
  }
  .alink:hover {
    border-bottom: 1px solid #7ef704;
    color:#7ef704;
  }
</style>
