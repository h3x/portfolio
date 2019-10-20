<template>
<div>
<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <router-link class="navbar-item" :to="{ name: 'home'}"><img src="../assets/home.png"></router-link>

    <a role="button" @click="isOpen = !isOpen" v-bind:class="{'is-active': isOpen}" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu" v-bind:class="{'is-active': isOpen}"> 
    <div class="navbar-start"></div>

    <router-link class="navbar-item" :to="{ name: 'projects'}">Featured Projects</router-link>

    <router-link class="navbar-item" :to="{ name: 'cv'}">CV</router-link>

    <router-link class="navbar-item" :to="{ name: 'education'}">Education</router-link>

    <router-link class="navbar-item" :to="{ name: 'about'}">About</router-link>



    <div class="navbar-end">
      
      <router-link class="navbar-item" :to="{ name: 'contact'}"><img src="../assets/contact.png"></router-link>
    </div>
  </div>
  
</nav>    
    <hr />

</div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Menu extends Vue { 
  private isOpen = false;
}
</script>

<style scoped>
hr {
  width: 80%;
  margin: auto;
  margin-bottom: 20px;
  border-top: 2px solid lightgrey;
}
span {
  border: 1px solid black;
}
</style>
