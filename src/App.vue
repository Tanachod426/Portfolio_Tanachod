<template>
  <nav>
    <div class="navbar">
      <h2>Portfolio</h2>
      |
      <h2>About</h2>
    </div>
  </nav>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.navbar {
  padding: 20px;
  display: flex;
  justify-content: space-between;
  background-color: #c4c3c3;
  color: #3b3b3b;
}
</style>
