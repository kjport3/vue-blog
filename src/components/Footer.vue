<template>
    <footer>
        <div>
        <ul class="social-links">
            <li>
            <a
                href="https://www.github.com/kjport3"
                title="Github"
                target="_blank"
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
    </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
footer {
  background-color: #35495e;
  color: white;
  height: 140px;
  width: 100%;
}

a {
  color: #fff;
  font-size: 160%;
}

ul {
  list-style: none;
  float: right;
  margin: 45px 0 0 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

div {
    max-width: 840px;
    margin: 0 auto;
}
</style>
