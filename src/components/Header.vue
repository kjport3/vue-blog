<template>
    <header>
        <nav>
            <a href="/"><img src="http://www.kennyporterfield.com/resources/img/kp-logo-black.png" /></a>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/blog">Blog</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header'
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

</style>