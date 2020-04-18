<template>
  <div class="article">
     <el-card class="box-card">
      <h5 class="clearfix">
        <div class="header">
          <span class="type">原创</span>
          <a class="title" href="#">测试数据</a>
          <span class="auther">作者： xiaoyu</span>
          <div class="riqi"><span class="updateTime">2020-04-17 22:08</span></div>
        </div>
      </h5>
      <hr style="margin:10px 0">
      <div class="bio">
        vue引入自定义组件失效，效果同未引入组件前
      </div>
      <hr style="margin:10px 0">
      <div class="footer">
        <div class="category">
          分类：<a href="">测试分类</a>
        </div>
        <div class="tags">
          <a href="">test</a>
          <a href="">test</a>
          <a href="">test</a>
        </div>
      </div>
    </el-card>
    <el-card class="box-card">
      <h5 class="clearfix">
        <div class="header">
          <span class="type">原创</span>
          <a class="title" href="#">测试数据</a>
          <span class="auther">作者： xiaoyu</span>
          <div class="riqi"><span class="updateTime">2020-04-17 22:08</span></div>
        </div>
      </h5>
      <hr style="margin:10px 0">
      <div class="bio">
        vue引入自定义组件失效，效果同未引入组件前
      </div>
      <hr style="margin:10px 0">
      <div class="footer">
        <div class="category">
          分类：<a href="">测试分类</a>
        </div>
        <div class="tags">
          <a href="">test</a>
          <a href="">test</a>
          <a href="">test</a>
        </div>
      </div>
    </el-card>
    <el-card class="box-card">
      <h5 class="clearfix">
        <div class="header">
          <span class="type">原创</span>
          <a class="title" href="#">测试数据</a>
          <span class="auther">作者： xiaoyu</span>
          <div class="riqi"><span class="updateTime">2020-04-17 22:08</span></div>
        </div>
      </h5>
      <hr style="margin:10px 0">
      <div class="bio">
        vue引入自定义组件失效，效果同未引入组件前
      </div>
      <hr style="margin:10px 0">
      <div class="footer">
        <div class="category">
          分类：<a href="">测试分类</a>
        </div>
        <div class="tags">
          <a href="">test</a>
          <a href="">test</a>
          <a href="">test</a>
        </div>
      </div>
    </el-card>
    <el-card class="box-card">
      <h5 class="clearfix">
        <div class="header">
          <span class="type">原创</span>
          <a class="title" href="#">测试数据</a>
          <span class="auther">作者： xiaoyu</span>
          <div class="riqi"><span class="updateTime">2020-04-17 22:08</span></div>
        </div>
      </h5>
      <hr style="margin:10px 0">
      <div class="bio">
        vue引入自定义组件失效，效果同未引入组件前
      </div>
      <hr style="margin:10px 0">
      <div class="footer">
        <div class="category">
          分类：<a href="">测试分类</a>
        </div>
        <div class="tags">
          <a href="">test</a>
          <a href="">test</a>
          <a href="">test</a>
        </div>
      </div>
    </el-card>
    <el-pagination
      background
      layout="prev, pager, next"
      :total="1000" style="margin-top:15px;text-align:center">
    </el-pagination>
  </div>
</template>

<script>
export default {
  name: 'article'
}
</script>

<style scoped>
  .category {
    float: left;
    color: #909399;
    margin-left: 15px;
  }
  .auther {
    color: #909399;
    margin-left: 15px;
    display: inline-block;
    height: 30px;
    line-height: 40px;
  }
  .footer {
    overflow: hidden;
  }
  .category a:hover ,.tags a:hover {
    background: #7ef704;
  }
  .category a {
    margin: 0 0 !important;
  }
  .category a,.tags a {
    text-decoration-line: none;
    border-radius: 7px;
    padding: 0 7px;
    background-color: #f1f2f0;
    color: #787977;
    line-height: 23px;
    margin-left:15px;
    display: inline-block;
    height: 23px;
    float: right;
  }
  .riqi {
    font-family: serif;
    color: #909399;
    height: 30px;
    float: right;
    line-height: 30px;
  }

  .bio {
    padding: 20px 0;
    margin-left: 15px;

  }
  .type {
    line-height: 30px;
    text-align: center;
    border-radius: 5px;
    display: inline-block;
    padding: 0px 5px;
    height: 25px;
    background: #787977;
    color: #ffffff;
    margin-left: 5px;
    font-size: 13px;
  }
  .header a{
    font-family: serif;
    text-decoration-line: none;
    color: #000;
    display: inline-block;
    font-size: 25px;
  }
  .title:hover {
    color: #7ef704;
  }
  .text {
    font-size: 14px;
  }

  .item {
    margin-bottom: 18px;
  }

 .clearfix {
   padding: 0;
   box-sizing: border-box;
 }

  .clearfix:before,
  .clearfix:after {
    display: table;
    content: "";
  }
  .clearfix:after {
    clear: both
  }

  .box-card {
    margin: 0 auto;
    width: 90%;
    margin-top: 20px;
  }
</style>
