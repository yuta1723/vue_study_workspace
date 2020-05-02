<template>
  <div id="app">

    <div id="header">
      <!--リンクタグを生成します。-->
      <router-link to="/page1">top</router-link>
      <router-link to="/page2">about</router-link>
      <router-link to="/page3">contact</router-link>
    </div>
    <!--上記のリンクタグで設定したコンポーネントが表示される場所です。-->
    <router-view></router-view>

<!--    <img src="./assets/logo.png">-->
<!--    <router-view/>-->
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
