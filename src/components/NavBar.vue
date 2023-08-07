  <script setup lang="ts">
  import { RouterLink } from 'vue-router';

</script>
<template>
  <nav class="pl-[100px] pr-[150px] py-[10px] flex items-center justify-between relative z-[1]">
    <!-- Logo -->
    <img class="w-40 h-9" src="../assets/logo/GoAdventure лого горизонтальный цветной.png" alt="" />

    <!-- Links -->
    <ul class="flex gap-[50px] justify-center">
      <li><RouterLink class="text-[#FD7043]" to="/">Home</RouterLink></li>
      <li><RouterLink class="text-black" to="/blog">Blog</RouterLink></li>
      <li><RouterLink class="text-black" to="/spo">SPO</RouterLink></li>
    </ul>

    <!-- Button -->
    <button class="w-[100px] h-[50px]  rounded-[15px] gradient-background text-white">BOOK</button>
  </nav>
</template>
