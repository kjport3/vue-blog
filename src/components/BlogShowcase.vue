<template>
  <div class="section">
    <ul>
      <li>
        <figure>
          <a href="post/39"
            ><img
              src="http://www.kennyporterfield.com/resources/img/rocket.png"
              alt="JavaScript Oddities: NaN"
          /></a>
          <div class="centered-text hide">
            <a href="post/39">JavaScript Oddities: NaN</a>
          </div>
        </figure>
      </li>
      <li>
        <figure>
          <a href="post/38"
            ><img
              src="http://www.kennyporterfield.com/resources/img/nextjs-circle.png"
              alt="Next.js Continued"
          /></a>
          <div class="centered-text hide">
            <a href="post/38">Next.js Continued</a>
          </div>
        </figure>
      </li>
      <li>
        <figure>
          <a href="post/37"
            ><img
              src="http://www.kennyporterfield.com/resources/img/recursion.jpg"
              alt="Recursive Functions"
          /></a>
          <div class="centered-text hide">
            <a href="post/37">Recursive Functions</a>
          </div>
        </figure>
      </li>
      <li>
        <figure>
          <a href="post/35"
            ><img
              src="http://www.kennyporterfield.com/resources/img/nextjs.jpg"
              alt="Exploring Next.js"
          /></a>
          <div class="centered-text hide">
            <a href="post/35">Exploring Next.js</a>
          </div>
        </figure>
      </li>
    </ul>
    <ul>
      <li>
        <figure>
          <a href="post/33"
            ><img
              src="http://www.kennyporterfield.com/resources/img/frequencies.jpg"
              alt="Frequency Counter Algorithm Pattern"
          /></a>
          <div class="centered-text hide">
            <a href="post/33">Frequency Counter Algorithm Pattern</a>
          </div>
        </figure>
      </li>
      <li>
        <figure>
          <a href="post/31"
            ><img
              src="http://www.kennyporterfield.com/resources/img/undraw_logic_sq.png"
              alt="Sorting Algorithms &amp; Optimizing Optimistically"
          /></a>
          <div class="centered-text hide">
            <a href="post/31"
              >Sorting Algorithms &amp; Optimizing Optimistically</a
            >
          </div>
        </figure>
      </li>
      <li>
        <figure>
          <a href="post/28"
            ><img
              src="http://www.kennyporterfield.com/resources/img/scope-sq.jpg"
              alt="YDKJS: Scope &amp; Closures"
          /></a>
          <div class="centered-text hide">
            <a href="post/28">YDKJS: Scope &amp; Closures</a>
          </div>
        </figure>
      </li>
      <li>
        <figure>
          <a href="post/20"
            ><img
              src="http://www.kennyporterfield.com/resources/img/bubble_sort.png"
              alt="Sorted Arrays, Binary Search, &amp; Big O"
          /></a>
          <div class="centered-text hide">
            <a href="post/20">Sorted Arrays, Binary Search, &amp; Big O</a>
          </div>
        </figure>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "BlogShowcase",
};
</script>

<style scoped>
ul {
  list-style: none;
  width: 100%;
  max-width: 940px;
  margin: auto;
  zoom: 1;
}
ul li {
  display: inline-block;
  padding: 0 3px;
  width: 24%;
}
ul::after {
  content: ".";
  clear: both;
  display: block;
  height: 0;
  visibility: hidden;
}
figure {
  width: 100%;
  margin: 0;
  overflow: hidden;
  background-color: white;
  position: relative;
  text-align: center;
  color: white;
}
a {
  border: none;
  color: white;
  text-decoration: none;
  background-color: transparent;
}
a:hover {
  color: white;
}
* {
    box-sizing: border-box;
}
img {
  opacity: 1;
  width: 100%;
  height: auto;
  border: 0;
}
img:hover {
  transform: scale(1.03);
  transition: transform 0.5s, opacity 0.5s;
}
.centered-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-shadow: 2px 2px #000000;
  font-size: 135%;
  color: white;
}
.hide {
  visibility: hidden;
}
figure:hover .hide {
  visibility: visible;
}
.section {
  margin: 40px 0;
  z-index: 1;
}
figure:hover {
  background-color: #000000;
}
figure img {
  opacity: 1;
  width: 100%;
  height: auto;
  -webkit-transform: scale(1.06);
  -ms-transform: scale(1.06);
  transform: scale(1.06);
  -webkit-transition: -webkit-transform 0.5s, opacity 0.5s;
  transition: transform 0.5s, opacity 0.5s;
}
figure:hover > a img {
  opacity: 0.7;
  -webkit-transform: scale(1.15);
  -ms-transform: scale(1.15);
  transform: scale(1.15);
}
</style>
