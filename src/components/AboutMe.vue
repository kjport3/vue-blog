<template>
  <div>
    <h1>About Me</h1>
    <p>
      Hello! My name is Kenny Porterfield and I am a web developer living in
      Atlanta, Georgia. I like to spend my time running, reading, learning, and
      growing as a developer. Fun facts about me: I have run an average of over
      2,000 miles a year for the last 5 years. In 2014 I thru-hiked the 2,200
      miles of the Appalachian Trail over 4 months. I read 70 books last year.
      And I am currently a Senior Campaign Developer at Digital Additive.
    </p>
    <ul class="social-links">
      <li>
        <a href="https://www.github.com/kjport3" title="Github" target="_blank"
          ><i class="fab fa-github"></i
        ></a>
      </li>
      <li>
        <a
          href="https://www.linkedin.com/in/kenporterfield/"
          title="LinkedIn"
          target="_blank"
          ><i class="fab fa-linkedin-in"></i
        ></a>
      </li>
      <li>
        <a href="./rss.xml" title="Subscribe via RSS" target="_blank"
          ><i class="fas fa-rss"></i
        ></a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>

<style scoped>
div {
  max-width: 640px;
  margin: 0 auto;
}
h1 {
  margin: 20px 0 20px 0;
}
p {
    margin: 0 0 20px 0;
}
a {
  color: #2c3e50;
  font-size: 160%;
}

ul {
  list-style: none;
}

li {
  display: inline-block;
  margin: 0 10px;
}
</style>
