<script setup lang="ts">
</script>

<template>
    <div class="h-screen flex gap-4  bg-slate-950 p-5 overflow-hidden text-white">
        <SideProfile />


        <main class="grow flex flex-col w-full rounded-md overflow-x-hidden overflow-y-auto scroll-smooth">

            <!-- Role -->
            <Role />
            <!-- Tech Stack -->
            <TechStack />
            <!-- About -->
            <About />

            <!-- projects -->
            <section class="p-5 mt-10">
                <h1 id="Projects" class="text-3xl font-rubik-mono mb-5">#Projects</h1>


                <!-- card container -->
                <section class="grid-cols-2 grid gap-1">
                    <div class="flex flex-col p-2 gap-2">
                        <img src="https://placehold.co/600x400" alt="" class="size-full rounded-lg">

                        <div>
                            <p>Title</p>
                            <p>tech-stack</p>
                            <p>type</p>
                        </div>
                    </div>
                    <div class="flex flex-col p-2 gap-2">
                        <img src="https://placehold.co/600x400" alt="" class="size-full rounded-lg">

                        <div>
                            <p>Title</p>
                            <p>tech-stack</p>
                            <p>type</p>
                        </div>
                    </div>
                </section>
            </section>
        </main>
        <SideNav />

    </div>
</template>