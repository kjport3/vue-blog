<template>
    <h1>Blog time</h1>
    <BlogShowcase />
    <div></div>
    
</template>

<script>
import BlogShowcase from '../components/BlogShowcase.vue'

export default {
    name: 'Blog',
    components: {
        BlogShowcase
    }
}
</script>

<style scoped>
h1 {
    text-align: center;
}
div {
    height:300px;
}
</style>