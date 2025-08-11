<script setup lang="ts">
</script>

<template>
    <div class="h-screen flex gap-4  bg-slate-950 p-5 overflow-hidden text-white">
        <SideProfile />


        <main class="grow flex flex-col w-full rounded-md overflow-x-hidden overflow-y-auto">

            <!-- Role -->
            <Role/>
            <!-- Tech Stack -->
            <TechStack/>
        </main>


        <SideNav />

    </div>
</template>