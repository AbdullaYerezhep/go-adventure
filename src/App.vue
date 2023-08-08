<script setup lang="ts">
import NavBar from './components/NavBar.vue'
import Hero from './components/Hero.vue'
import Why from './components/Why.vue'
import Blog from './components/Blog.vue'
import About from './components/About.vue'
</script>

<template class="w-full h-vh">
  <div class="flex-col w-full h-full bg-white">
    <NavBar/>
    <Hero/>
    <Why/>
    <Blog/>
    <About/>
  </div>
</template>

<style scoped>
</style>
