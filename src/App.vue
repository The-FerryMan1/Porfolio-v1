<script setup lang="ts">
import HeadNav from './components/headNav.vue';
import Hero from './pages/Hero.vue';
import Marqueeness from './components/Marqueeness.vue';
import Projects from './components/Projects.vue';
import Footerness from './components/Footerness.vue';

</script>

<template>
  <UApp>
    <head-nav />
    <UMain>
      <Hero />
      <Marqueeness />
      <Projects/>
      <Footerness/>
    </UMain>

  </UApp>
</template>

<style scoped></style>
