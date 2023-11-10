<template>
  <main-page></main-page>
  <router-view />
</template>
<script>
import MainPage from "./components/MainPage.vue";
export default {
  name: "app",
  components: {
    MainPage,
  },
};
</script>

<style>
#app {
  padding: 0;
  margin: 0;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
