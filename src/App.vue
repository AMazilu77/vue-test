<template>
  <h1>Options Updater</h1>

  <div class="container">
    <Header />
    <getBody />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import getBody from "./components/getBody.vue";
export default {
  name: "App",
  components: {
    Header,
    getBody,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 75%;
  margin: 1%;
}
button {
  margin: 1%;
}

.container {
  width: 90%;
  padding: 5%;
}

h1 {
  padding: 1%;
}
</style>
