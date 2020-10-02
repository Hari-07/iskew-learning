<template>
  <div id="app">
    <NavMenu />
    <router-view/>
    <Footer />
  </div>
</template>

<script>
import NavMenu from '@/components/NavMenu.vue'
import Footer from '@/components/Footer.vue'

export default {
  name:'App',
  components:{
    NavMenu,
    Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap');

#app {
  font-family:'Open Sans', Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #111111;
  background: white;
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
</style>
