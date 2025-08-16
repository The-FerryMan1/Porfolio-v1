<script setup lang="ts">
const links = [
    'About',
    'Projects',
];
</script>

<template>
    <aside
        class="sm:w-1/12 w-full rounded-md overflow-hidden  font-rubik-mono bg-transparent text-white p-5 sm:order-3 order-1">
        <nav class="h-full ">
            <ul class="flex justify-center flex-row items-center h-full text-center sm:gap-35 sm:flex-col gap-2">
                <li v-for="link in links"
                    class="tracking-wider transform  sm:rotate-90 sm:text-xl text-sm hover:text-red-500 transition-colors duration-300 drop-shadow-sm">
                    <a :href="`#${link}`">{{ link }}</a>
                </li>
            </ul>
        </nav>
    </aside>
</template>