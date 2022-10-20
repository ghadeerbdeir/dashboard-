<template>
  <div class="box">
    <Home />
  </div>
</template>

<script>
import Home from "./views/Home.vue";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
  background-color: #f8fafb;
}
.box {
  height: 100rem;
  width: 100rem;
}

.box .content {
  height: 260px;
  width: 280px;
}
</style>
