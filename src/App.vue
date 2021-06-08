<template>
  <Header />
  <ProfilePic />
  <AboutMe />
  <BlogShowcase />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import ProfilePic from './components/ProfilePic.vue'
import AboutMe from './components/AboutMe.vue'
import BlogShowcase from './components/BlogShowcase.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    ProfilePic,
    AboutMe,
    BlogShowcase,
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
