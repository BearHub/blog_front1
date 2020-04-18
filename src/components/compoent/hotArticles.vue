<template>
    <div class="hotArticles">
        <span class="HotTitle">热门文章</span>
        <hr style="margin:10px 15px">
        <div class="hotList">
            <span class="xuhao">1</span><a href="#" class="hotT">测试文章</a>
        </div>
        <div class="hotList">
            <span class="xuhao">1</span><a href="#" class="hotT">测试文章</a>
        </div>
        <div class="hotList">
            <span class="xuhao">1</span><a href="#" class="hotT">测试文章</a>
        </div>
        <div class="hotList">
            <span class="xuhao">1</span><a href="#" class="hotT">测试文章</a>
        </div>
        <div class="hotList">
            <span class="xuhao">1</span><a href="#" class="hotT">测试文章</a>
        </div>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.hotList {
    margin-top: 10px;
}
.hotT:hover {
    color: #7ef704;
    border-bottom:1px solid #7ef704;
}
.hotT {
    display: inline-block;
    height:26px;
    font-size: 23px;
    text-decoration-line: none;
    color:#787977;
    padding-top: 5px
}
.xuhao {
    display: inline-block;
    width: 30px;
    height: 30px;
    background: #7ef704;
    border-radius: 15px;
    text-align: center;
    line-height: 30px;
    color:#fff;
    margin:0px 10px 0 15px;
}
.hotArticles {
    overflow: hidden;
}
.HotTitle {
    margin: 15px 0px 0 15px;
    font-size: 23px;
}
</style>
