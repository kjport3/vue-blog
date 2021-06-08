<template>
  <ProfilePic />
  <AboutMe />
  <BlogShowcase />
</template>

<script>
import ProfilePic from "@/components/ProfilePic.vue";
import AboutMe from "@/components/AboutMe.vue";
import BlogShowcase from "@/components/BlogShowcase.vue";

export default {
  name: "HomePage",
  components: {
    ProfilePic,
    AboutMe,
    BlogShowcase,
  },
};
</script>
