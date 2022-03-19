<template>
  <div id="app">
    <Menu />
    <router-view />
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import Menu from "@/components/Menu.vue";
export default Vue.extend({
  components: {
    Menu
  }
})
</script>

<style>
@import "../node_modules/bulma/css/bulma.min.css";

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

hr {
  width: 50%;
  margin: auto;
  border-top: 2px solid darkgrey;
  margin-top: 20px;
}

br {
  margin-top: 15px;
  margin-bottom: 15px;
}

section {
  margin-top: 30px;
  justify-content: left;
}

.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

p {
  margin-bottom: 5px;
}
h1 {
  font-size: 3em;
}

.language-logo {
  max-width: 150px;
}

.content {
  margin: auto;
  margin-left: 20%;
  margin-right: 20%;
}
</style>
