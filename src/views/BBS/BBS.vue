<!--
 * @Author: gooing
 * @since: 2020-03-11 00:30:09
 * @lastTime: 2020-03-15 14:04:36
 * @LastAuthor: gooing
 * @FilePath: \pixiciv-pc\src\views\BBS\BBS.vue
 * @message:
 -->
<template>
  <div class="bbs">
    <div class="iframe">
      <iframe src="https://discuss.pixivic.com/" width="100%" height="100%" frameborder="0">
        您的浏览器不支持iframe，请升级
      </iframe>
      <!-- <a href="https://discuss.pixivic.com/" target="_Blank">
        <el-button round size="small" type="primary">点击跳转</el-button>
      </a> -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'BBS'
};
</script>

<style scoped lang="less">
.bbs {
  height: calc(~"100vh - 60px");
  width: calc(~"100vw-65px");
  overflow: auto;
  background: #f5f5f5;
  display: flex;

  .iframe{
    height: 100%;
    width: 100%;
  }
}
</style>
