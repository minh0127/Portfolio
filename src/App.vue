<template>
  <HomeView></HomeView>
  <TheFooter></TheFooter>
</template>

<script>
import HomeView from "./views/HomeView.vue";
import TheFooter from "./components/TheFooter.vue";
export default {
  name: "App",
  components: { HomeView, TheFooter },
};
</script>

<style>
@import url("./assets/css/base.css");
</style>
