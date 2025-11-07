<script setup lang="ts">
import type { NavigationMenuItem } from '@nuxt/ui'
import { computed } from 'vue';
import { useRoute } from 'vue-router';

const route = useRoute()

const items = computed<NavigationMenuItem[]>(() => [
  {
    label: 'Home',
    
  },
  {
    label: 'Projects',
 
  },
  {
    label: 'Contacts',
  
  },
])
</script>

<template>
  <UHeader>
    <template #title>
      <h1>Rox//</h1>
    </template>

    <UNavigationMenu :items="items" />

    <template #right>
      <UColorModeButton />
    </template>
    <template #body>
      <UNavigationMenu :items="items" orientation="vertical" class="-mx-2.5" />
    </template>
  </UHeader>
</template>
