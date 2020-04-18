<template>
    <div class="category">
        <el-input class="input"
            placeholder="请输入内容">
        </el-input>
        <el-button icon="el-icon-search" circle></el-button>
        <div class="elCard">
            <el-card :body-style="{ padding: '13px'}" shadow="hover">
                <a href="#">全部文章</a>
            </el-card>
            <el-card :body-style="{ padding: '13px'}" shadow="hover">
                <a href="#">鼠标悬浮时显示</a>
            </el-card>
            <el-card :body-style="{ padding: '13px'}" shadow="hover">
                <a href="#">鼠标悬浮时显示</a>
            </el-card>
            <el-card :body-style="{ padding: '13px'}" shadow="hover">
                <a href="#">鼠标悬浮时显示</a>
            </el-card>
            <el-card :body-style="{ padding: '13px'}" shadow="hover">
                <a href="#">鼠标悬浮时显示</a>
            </el-card>
        </div>
    </div>
</template>

<script>
export default {
  name: 'category'
}
</script>

<style scoped>
.elCard a {
    text-align: center;
    display: inline-block;
    text-decoration-line: none;
    color:#787977;
    width: 100%;
    height: 100%;
}
.elCard a:hover {
    color:#d7dbd3;
}
.elCard {
    margin-top: 5px;
    font-size: 15px;
}
.input {
    width: 84%;
}
.category {
    padding: 0px 10px;
}
</style>
