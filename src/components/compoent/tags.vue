<template>
    <div class="Tags">
        <span class="tags">标签</span>
        <hr style="margin:10px 15px">
        <div class="tag">
          <a href="">test</a>
          <a href="">test</a>
          <a href="">test</a>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.tag a:hover {
    background-color:#7ef704;
}
.tag a {
    font-size: 23px;
    text-decoration-line: none;
    border-radius: 7px;
    padding: 0 7px;
    background-color: #f1f2f0;
    color: #787977;
    line-height: 25px;
    margin-left:15px;
    display: inline-block;
    height: 25px;
  }
.Tags {
    overflow: hidden;
}
.tags {
    margin: 15px 0px 0 15px;
    font-size: 23px;
}
</style>