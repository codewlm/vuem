<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="less">
*{
  margin: 0;
  padding: 0;
}
html, body{
  width: 100vw;
  height: 100vh;
}
body {
  background: url("https://vueschool.io/media/ffbaf4151052529c8a0d83c65c9a8e6e/the-vuejs-master-class.jpeg") no-repeat center / cover;
}
#app {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
}
</style>
