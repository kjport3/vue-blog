<template>
  <Header :homePage="homePage" :blogPage="blogPage" />
  <router-view />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
  },
  computed: {
    homePage() {
      if(this.$route.path === '/') {
        return true;
      } else {
        return false;
      }
    },
    blogPage() {
      if(this.$route.path === '/blog') {
        return true;
      } else {
        return false;
      }
    }
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

html, body {
  font-family: "Lato", "Arial", "Helvetica", sans-serif;
  font-style: normal;
  font-weight: 300;
}

p {
  font-size: 20px;
}

body::before {
  display:block;
  content: '';
  height:80px; /* or whatever */
}

* {
  margin: 0;
  padding: 0;
}

a:hover {
  color: #0D8D53;
}


</style>
