<script setup lang="ts">
const links = [
    {
        label: 'Get CV',
        to: '/docs/getting-started',
        icon: 'i-lucide-file-user'
    },
    {
        label: 'Projects',
        to: '/docs/getting-started/theme/design-system',
        color: 'neutral',
        variant: 'subtle',
        trailingIcon: 'i-lucide-arrow-right'
    }
]
</script>


<template>
    <UPageHero 
        title="Full-Stack Developer"
        description="Full-Stack Developer with six months of professional experience in a dynamic environment, successfully delivering key features from concept to production deployment. I am proficient in modern architectural principles and committed to building scalable solutions that address real-world challenges."
        :links
    />
</template>