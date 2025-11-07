<script setup lang="ts">
import { ref } from 'vue';

const links = [
    {
        label: 'Check Repository',
        icon: 'i-lucide-github'
    }
]
</script>

<template>
    <UPageSection title="Projects" :links
        description="Check out the collection of projects I made throughout my journey to enhance and improve my skill in this profession. ">
        <UPageColumns>
            <UPageCard title="Link Shortener | Personal Project"
                description="Stack: Vue.JS, Elysia.JS, Bun.JS, TailwindCSS" spotlight spotlight-color="primary">
                  <img src="../assets/img/URlSHORTENER.png" alt="" class="">
                <template #footer>
                    <p>No preview available</p>
                </template>
            </UPageCard>
        </UPageColumns>
    </UPageSection>
</template>
