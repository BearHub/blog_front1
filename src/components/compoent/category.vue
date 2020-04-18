<template>
    <div class="category">
        <el-input class="input"
            placeholder="请输入内容">
        </el-input>
        <el-button icon="el-icon-search" circle></el-button>
        <hr style="margin:15px 0px 0px 0px">
        <div class="elCard">
            <div class="cates">
                <a href="#" class="cate">测试文章</a>
                <hr style="margin:14px 0px 0px 0px">
            </div>
            <div class="cates">
                <a href="#" class="cate">测试文章</a>
                <hr style="margin:14px 0px 0px 0px">
            </div>
            <div class="cates">
                <a href="#" class="cate">测试文章</a>
                <hr style="margin:14px 0px 0px 0px">
            </div>
            <div class="cates">
                <a href="#" class="cate">测试文章</a>
                <hr style="margin:14px 0px 0px 0px">
            </div>
            <div class="cates">
                <a href="#" class="cate">测试文章</a>
                <hr style="margin:14px 0px 0px 0px">
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'category'
}
</script>

<style scoped>
.cate {
    display: inline-block;
    height:26px;
    font-size: 23px;
    text-decoration-line: none;
    color:#787977;
    padding-top: 5px;
    margin-left:15px;
}
.elCard a:hover {
    color:#d7dbd3;
}
.elCard {
    overflow: hidden;
    font-size: 15px;
}
.input {
    width: 83%;
}
.category {
    padding: 0px 10px;
}
</style>
