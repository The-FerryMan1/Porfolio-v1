<script setup lang="ts">
</script>

<template>
    <div class="h-screen flex gap-4  bg-slate-950 p-5 overflow-hidden text-white">
        <SideProfile />


        <main class="grow w-full rounded-md overflow-x-hidden overflow-y-auto">

            <!-- Role -->
            <section class="py-10 px-2 ">
                <h1 class="font-rubik-mono text-7xl text-wrap">
                    <span class="text-black text-shadow-md text-shadow-white text-shadow-">Full-Stack </span>
                    Web Devopler
                </h1>
            </section>
            <!-- Tech Stack -->
            <section class="w-full">
                <div class="relative flex overflow-x">
                    <div class="animate-marquee py-12 whitespace-nowrap flex gap-30 font-rubik-mono text-lg">
                        <span class="mx-4 text-4xl flex gap-4 justify-start items-center">
                            <img src="../assets/img/Nuxt_logo.png" alt="" class="size-18 aspect-auto">
                            <p>NUXT</p>
                        </span>
                        <span class="mx-4 text-4xl  flex gap-4 justify-start items-center ">
                            <img src="../assets/img/HTML5_logo_and_wordmark.png" alt="" class="size-18 aspect-auto">
                            HTML</span>
                        <span class="mx-4 text-4xl  flex gap-4 justify-start items-center">
                            <img src="../assets/img/Official_css_logo.png" alt="" class="size-18 aspect-auto">
                            CSS
                        </span>
                        <span class="mx-4 text-4xl  flex gap-4 justify-start items-center">
                            <img src="../assets/img/tailwindcss-mark.svg" alt="" class="size-18 aspect-auto">
                            TAILWIND
                        </span>
                        <span class="mx-4 text-4xl  flex gap-4 justify-start items-center">
                            <img src="../assets/img/vue.svg" alt="" class="size-18 aspect-auto">
                            VUE
                        </span>
                        <span class="mx-4 text-4xl  flex gap-4 justify-start items-center">
                            <img src="../assets/img/hono.svg" alt="" class="size-18 aspect-auto">
                            Hono
                        </span>
                        <span class="mx-4 text-4xl  flex gap-4 justify-start items-center">
                            <img src="../assets/img/Laravel.png" alt="" class="size-18 aspect-auto">
                            LARAVEL
                        </span>
                        <span class="mx-4 text-4xl  flex gap-4 justify-start items-center">
                            <img src="../assets/img/Typescript.png" alt="" class="size-18 aspect-auto">
                            TYPESCRIPT
                        </span>
                    </div>
                </div>
            </section>
        </main>


        <SideNav />

    </div>
</template>