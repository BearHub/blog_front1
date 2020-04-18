<template>
  <div id="app">
    <el-container>
      <el-header><navBar></navBar></el-header>
      <el-main><router-view /></el-main>
      <el-footer><Footer/></el-footer>
    </el-container>
  </div>
</template>

<script>
import navBar from '@/components/compoent/navBar'
import Footer from '@/components/compoent/footer'

export default {
  name: 'app',
  components: {
    navBar,
    Footer
  }
}
</script>

<style>
@import '../static/font/font.css';

* {
  margin:0;
  padding: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.el-header, .el-footer {
    background-color: #fff;
    color: #333;
    text-align: center;
    line-height: 60px;
    padding: 0px;
    line-height: 60px;
  }

  .el-main {
    background-image: url('./assets/bg.gif');
    background-repeat: repeat;
    color: #333;
  }

  body > .el-container {
    margin-bottom: 40px;
  }

</style>
