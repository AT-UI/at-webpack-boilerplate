<template>
  <div class="container" id="app">
    <div class="app">
      <img src="./assets/logo.png">
      <h1>Vue 2 & AT-UI</h1>
      <at-button @click="handleClick">Thanks for choosing AT-UI </at-button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    handleClick () {
      this.$Message('It works! We believe that you can save your time with AT-UI.')
    }
  }
}
</script>

<style lang="scss">
  .container {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
  .app {
    color: #2c3e50;
    text-align: center;
  }
  h1, h2 {
    font-weight: normal;
    margin: 16px 0;
  }
</style>
