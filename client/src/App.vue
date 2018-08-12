<template>
  <div id="app">
  <navbar></navbar>
  </div>
</template>

<script>
import navbar from '../src/components/navbar.vue'
export default {
  name: 'app',
  components: {
    navbar: navbar
  }
}
</script>

<style>
/* Color pallette used: #051e3e • #251e3e • #451e3e • #651e3e • #851e3e */ 
body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

main {
  text-align: center;
  margin-top: 40px;
}

header {
  margin: 0;
  height: 56px;
  padding: 0 16px 0 24px;
  background-color: #35495E;
  color: #ffffff;
}

header span {
  display: block;
  position: relative;
  font-size: 20px;
  line-height: 1;
  letter-spacing: .02em;
  font-weight: 400;
  box-sizing: border-box;
  padding-top: 16px;
}
</style>
