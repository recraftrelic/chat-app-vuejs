<template>
  <ChatApp></ChatApp>
</template>

<script>
import ChatApp from "./components/ChatApp.vue";

export default {
  name: "App",
  components: {
    ChatApp
  },
};
</script>

<style>
body {
  margin: 0px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 10px;
}
</style>
