<template>
  <h1>Dynamic Routing</h1>
  <!-- <Home /> -->
  <router-link to="/">Home</router-link><br>
  
  <router-link to="/login">Login</router-link> <br>
  <router-link to="/profile/folu">Folu's profile</router-link> <br>
  <router-link to="/profile/john">John's profile</router-link> <br>
  <router-link to="/profile/aelin">Aelin's profile</router-link> <br>
  <router-view />
</template>

<script>

// import Home from './components/Home.vue';
export default {
  name: 'App',
  components: {
    // Home,
    
  }
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
