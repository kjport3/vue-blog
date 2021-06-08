<template>
    <header>
        <nav>
            <router-link to="/"><img src="../assets/logo.png" /></router-link>
            <ul>
                <li><router-link to="/" :class="{ active: homePage }">Home</router-link></li>
                <li><router-link to="/blog" :class="{ active: blogPage }">Blog</router-link></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header',
    props: {
    homePage: Boolean,
    blogPage: Boolean,
  },
}
</script>

<style scoped>
header {
    position: fixed;
    width: 100%;
    text-align: right;
    top: 0;
    left: 0;
    border-bottom: 1px solid #ddd;
    background-color: rgba(255, 255, 255, 0.96);
    box-shadow: 0 2px 2px #efefef;
    z-index: 9999;
}

nav {
    max-width: 840px;
    margin: 0 auto;
}

img {
    height: 50px;
    width: auto;
    float: left;
    margin: 20px 0;
}

ul {
    list-style: none;
    display: block;
    float: right;
    width: 80%;
    margin-top: 12px;
}

li {
    display: inline-block;
    padding: 20px 0 20px 30px;
    font-size: 24px;
}

a {
    color: #2c3e50;
    text-decoration: none;
    padding-bottom: 8px;
}

a:hover {
    color: #41b883;
    border-bottom: 2px solid #41b883;
}

.active {
    border-bottom: 2px solid #0D8D53;
}

@media only screen and (max-width: 880px) {
    nav {
        max-width: 90%;
    }
}

</style>