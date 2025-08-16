<script setup lang="ts">
</script>

<template>
    <div class="h-screen flex gap-4  bg-slate-950 sm:p-5 text-white sm:flex-row flex-col">
        <SideProfile />


        <main
            class="grow flex flex-col rounded-md overflow-x-hidden sm:overflow-y-auto scroll-smooth mostly-customized-scrollbar sm:order-2 order-3">

            <!-- Role -->
            <Role />
            <!-- Tech Stack -->
            <TechStack />
            <!-- About -->
            <About />
            <!-- projects -->
            <Projects />
            <Footer/>
        </main>
        <SideNav />

    </div>
</template>