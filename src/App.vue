<script setup>
import Header  from './components/sections/header.vue';
import Slider  from './components/sections/Slider.vue';
import How  from './components/sections/How.vue';
import About  from './components/sections/About.vue';
import Apps  from './components/sections/Apps.vue';
import Auto  from './components/sections/Auto.vue';
import Client  from './components/sections/Client.vue';
import Footer  from './components/sections/Footer.vue';
</script>

<template>
<div class="hero_area">
  <Header/>
  <Slider/>
</div>
  <How/>
  <About/>
  <Apps/>
  <Auto/>
  <Client/>
  <Footer/>
</template>

<style scoped>
</style>
