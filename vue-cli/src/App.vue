<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <!-- 컴포넌트 네이밍 컨벤션 종류 -->
    <!-- 케밥 케이스 -->
    <hello-world></hello-world>
    <!-- 파스칼 케이스 -->
    <HelloWorld></HelloWorld>
    <!-- 파스칼 케이스 -->
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

// export default = new Vue 라고 볼 수 있다
export default {
  // 인스턴스 옵션 속성 또는 컴포넌트 옵션 속성을 넣어 사용한다
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
