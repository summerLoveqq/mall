<template>
  <div class="nav-bar">
    <div class="left"><slot name="left"></slot></div>
    <div class="center"><slot name="center"></slot></div>
    <div class="right"><slot name="right"></slot></div>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style lang="less" scoped>
.nav-bar {
  display: flex;
  height: 80px;
  line-height: 80px;
  .left {
    width: 120px;
    background: red;
  }
  .right {
    width: 120px;
    background: red;
  }
  .center {
    flex: 1;
    font-size: 40px;
  }
}
</style>