<script setup lang="ts">

</script>

<template>
  <UFooter>
    <template #left>
      <p class="text-muted text-sm">Copyright © {{ new Date().getFullYear() }}</p>
    </template>

    <!-- <UNavigationMenu :items="items" variant="link" /> -->

    <template #right>
        <p class="text-muted text-sm text-left">Disclaimer: All third-party trademarks, logos, and brand names used on this site are the property of their respective owners</p>
    </template>
  </UFooter>
</template>
