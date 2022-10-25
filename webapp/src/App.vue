<template>
  
  <Navbar-Item></Navbar-Item>
</template>

<script setup>

import NavbarItem from './components/Navbar-Item.vue'


  name: 'App'
  const components = () => {
    NavbarItem
  }


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
