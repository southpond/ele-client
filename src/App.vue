<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="less">
@import "./assets/css/base.less";
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  > div {
    padding-top: 46px;
    padding-bottom: 46px;
  }
}
</style>
