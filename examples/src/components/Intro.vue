<template>
  <div>
    <div class="bottom-right-button"
    style="position: fixed;
    bottom: 35px;
    right: 30px;
    opacity: 0.5;
    z-index: 5;">
        <a class="bottom-right-button-link js-bottom-right-button-link" href="#">
          <img class="bottom-right-icon" src="/images/right-bottom-button.png" style="width: 40px; height: 40px;">
        </a>
    </div>
    <div class="title-container center mw7 ph3">
      <h1 class="title f1-ns f3 tc pt3 pt5-ns lh-title">
        How to write X in both Python 3 and JavaScript (ES2015)
      </h1>
    </div>
    <div class="header-text-container center mw7 pb3 ph3">
      <p class="header-text f4-ns">Python and JavaScript are <a href="https://stackoverflow.blog/2017/09/06/incredible-growth-python/">two of the most popular programming languages</a>.
   If you're are Python programmer learning JavaScript, or a JavaScript programmer learning Python, this handy cheat sheet might help you.</p><p class="header-text f4-ns">This page is open sourced on <a href="https://github.com/sayazamurai/python-vs-javascript">GitHub</a>. Pull requests are welcome!</p>
        <p class="tc"><!-- Place this tag where you want the button to render. -->
  <a class="github-button" href="https://github.com/sayazamurai/python-vs-javascript" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star sayazamurai/python-vs-javascript on GitHub">Star</a></p>
    </div>
    <div class="about-the-author center mw7 pb3 ph3">
      <h2 class="tc f3-ns f4 mb2">About the Author</h2>
      <div class="center tc mb3">
        <img class="ba b--white bw2 dib br4" src="/images/saya-profile.jpg" width="130" height="130" />
      </div>
      <p class="profile-text mw6 center mt0">
        I'm Saya, a jewelry designer and a junior JavaScript/Python developer living in Tokyo. Find me on Twitter: <a href="https://twitter.com/sayajewels">@sayajewels</a>
      </p>
      <p class="profile-text mw6 center mt0">
         <blockquote class="twitter-tweet tw-align-center" data-cards="hidden"  data-lang="en">
           <p lang="en" dir="ltr">If you&#39;re are Python programmer learning JavaScript, or a JavaScript programmer learning Python, this handy cheat sheet might help you. Pull requests are welcome! 🐥 ✨
             <br><br>How to write X in both Python 3 and JavaScript (ES2015)<a href="https://t.co/F3MScUMheC">https://t.co/F3MScUMheC</a>
           </p>
           <p>&mdash; Saya (@sayajewels) <a href="https://twitter.com/sayajewels/status/1040602212718632960?ref_src=twsrc%5Etfw">September 14, 2018</a></p>
         </blockquote>

      </p>
      <p class="profile-text mw6 center mt0">
        <strong>See also:</strong> Ilya Schurov has made a <a href="https://ischurov.github.io/pythonvjs/">similar page</a> - check it out!
      </p>
    </div>
    <div class="tabele-of-contents center mw7 pb3 ph3 mb4">
      <h2 class="tc f3-ns f4 mb2">Table of Contents</h2>
      <ul class="list pl0 tc">
        <li class="dib mh2"><a href="#math">Math</a></li>
        <li class="dib mh2"><a href="#control-flow">Control Flow</a></li>
        <li class="dib mh2"><a href="#string">String</a></li>
        <li class="dib mh2"><a href="#list">List/Array</a></li>
        <li class="dib mh2"><a href="#dictionary">Dictionary/Object</a></li>
        <li class="dib mh2"><a href="#function">Function</a></li>
        <li class="dib mh2"><a href="#class">Class</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Intro',
  props: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
