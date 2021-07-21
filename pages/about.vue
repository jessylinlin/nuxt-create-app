<template>
  <div>
    <h1>about page</h1>
    <!-- 1、a标签 -->
    <h2>a</h2>
    <a href="/">首页</a>

    <h2>router-link</h2>
    <router-link to="/">首页</router-link>

    <h2>编程式导航</h2>
    <button @click="gotoHome">首页</button>
  </div>
</template>
<script>
export default {
  name: "AboutPage",
  methods: {
    gotoHome() {
      this.$router.push("/");
    },
  },
};
</script>
<style scoped>
</style>