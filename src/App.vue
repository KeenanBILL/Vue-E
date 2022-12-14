<template>
  <NavBar />
  <router-view />
  <Footer />
</template>

<script>
import NavBar from '../src/components/NavBar.vue';
import Footer from '../src/components/Footer.vue';

export default {
  components: {
    NavBar, Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #023047;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #023047;
}

nav a.router-link-exact-active {
  color: #219EBC;
}
</style>
