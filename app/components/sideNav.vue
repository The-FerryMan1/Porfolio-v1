<script setup lang="ts">
const links = [
    'Home',
    'About',
    'Projects',
];
</script>

<template>
    <aside
        class="w-1/12  rounded-md overflow-hidden  font-rubik-mono bg-transparent text-white p-5">
        <nav class="h-full ">
            <ul class="flex justify-center flex-col items-center h-full text-center gap-35">
                <li v-for="link in links"
                    class="tracking-wider transform rotate-90 text-xl hover:opacity-50 transition-opacity duration-300 drop-shadow-sm">
                    <a :href="`#${link}`">{{ link }}</a>
                </li>
            </ul>
        </nav>
    </aside>
</template>