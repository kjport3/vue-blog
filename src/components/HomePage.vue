<template>
  <ProfilePic />
  <AboutMe />
  <BlogShowcase />
</template>

<script>
import ProfilePic from "./ProfilePic.vue";
import AboutMe from "./AboutMe.vue";
import BlogShowcase from "./BlogShowcase.vue";

export default {
  name: "HomePage",
  components: {
    ProfilePic,
    AboutMe,
    BlogShowcase,
  },
};
</script>
