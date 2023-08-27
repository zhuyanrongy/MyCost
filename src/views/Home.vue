<template>
  <h1>{{ msg }}</h1>
</template>

<script>
import { ref } from "vue";
export default {
  name: "Home",
  setup(props) {
    let msg = ref("我是Home组件");
    return {
      msg,
    };
  },
};
</script>

<style>
</style>