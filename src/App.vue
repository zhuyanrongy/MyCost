<script>
export default {
  name: "App",
};
</script>

<template>
  <h1>我是app组件</h1>
  <router-link :to="'/'">去Home页面</router-link>
  <br />
  <router-link :to="'/about'">去About页面</router-link>
  <router-view></router-view>
</template>

<style scoped>
</style>
