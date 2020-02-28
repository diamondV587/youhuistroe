<template>
  <div id="app">
    <div class="search-wrapper">
      <div class="logo-box">
        <img class="logo-images" src="../static/images/logo2.png" alt="logo" />
      </div>
      <div class="serach-box">
        <input type="text" value="请输入你要查询的内容">
      </div>
      <div class="download-box">
        <a href="javascript:void(0)">下载</a>
      </div>
    </div>
    <router-view />
  </div>
</template>

<script>
  export default {
    name: 'App',
    components: {}
  }

</script>

<style>
  @import "../static/css/common.css";
  @import "../static/css/search.css";

</style>
