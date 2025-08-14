<script setup lang="ts">
</script>

<template>
    <div class="h-screen flex gap-4  bg-slate-950 p-5 overflow-hidden text-white">
        <SideProfile />


        <main
            class="grow flex flex-col w-full rounded-md overflow-x-hidden overflow-y-auto scroll-smooth mostly-customized-scrollbar">

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