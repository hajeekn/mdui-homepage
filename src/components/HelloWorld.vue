<template>
  <div class="projects">
    <center>
      <p class="sustext">
        {{ msg }}
      </p>
    </center>
    <div class="mdui-panel" mdui-panel>
      <div class="mdui-panel-item">
        <div class="mdui-panel-item-header">
          <p>Yinaal - Web Tools</p>
        </div>
      </div>
      <div class="mdui-panel-item">
        <div class="mdui-panel-item-header">
          <p>Mdui HomePage - 基于 Vue 的简单个人主页</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
h3
  margin 40px 0 0

ul
  list-style-type none
  padding 0

li
  display inline-block
  margin 0 10px

a
  color #42b983
</style>
