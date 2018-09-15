<template>
  <div class="Q02 cf ph2-ns mb4-ns mb3">
    <h3 class="tc normal f3-ns f4 mb2">Math: <strong>Round Numbers</strong></h3>
    <div class="fl w-100 w-50-l pa2 mb3">
      <h4 class="f5 mt0 mb2 normal"><strong>Python 3</strong> / <a href="https://docs.python.org/3/library/math.html#math.ceil"><code>ceil</code></a>, <a href="https://docs.python.org/3/library/math.html#math.floor"><code>floor</code></a>, <a href="https://docs.python.org/3/library/functions.html#round"><code>round</code></a></h4>
      <div class="overflow-auto ba bw2 b--white br4">
        <pre><code class="language-python">import math

# 2
print(math.ceil(1.5))
# 1
print(math.floor(1.5))
# 2
print(round(1.5))
</code></pre>
      </div>
    </div>
    <div class="fl w-100 w-50-l pa2 mb3">
      <h4 class="f5 mt0 mb2 normal"><strong>JavaScript (ES2015)</strong> / <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/ceil"><code>ceil</code></a>, <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor"><code>floor</code></a>, <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/round"><code>round</code></a></h4>
      <div class="overflow-auto ba bw2 b--white br4">
        <pre><code class="language-javascript">// 2
console.log(Math.ceil(1.5))
// 1
console.log(Math.floor(1.5))
// 2
console.log(Math.round(1.5))
</code></pre>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AbsoluteValue',
  props: {},
  watch: {
  // Note : paste.content is declared as string and assume paste is defined in Vue data
  'paste.content': function(value) {
    let editor = document.querySelector('#editor code');
    editor.innerHTML = value;
    this.$nextTick(()=> Prism.highlightElement(editor));
  }
}
}
</script>

<style>


</style>
