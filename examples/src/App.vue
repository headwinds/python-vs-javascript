<template>
  <div id="app">
    <!--<div id="nav">
      <router-link to="/">home</router-link> |
      <router-link to="/math">math</router-link>
    </div>
    <router-view/>-->
    <Intro />
    <AbsoluteValue />
    <RoundNumbers />
  </div>
</template>

<script>
import Vue from 'vue'
import VuePrism from 'vue-prism'
import Intro from '@/components/Intro.vue'
import AbsoluteValue from '@/components/math/AbsoluteValue.vue'
import RoundNumbers from '@/components/math/RoundNumbers.vue'

Vue.use(VuePrism)

import 'prismjs/themes/prism.css'

export default {
  name: 'App',
  components: {
    Intro,
    AbsoluteValue,
    RoundNumbers
  },
  props: {}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.ba {
  background: #f5f2f0
}

</style>
