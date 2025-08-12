<script setup lang="ts">
</script>

<template>
    <div class="h-screen flex gap-4  bg-slate-950 p-5 overflow-hidden text-white">
        <SideProfile />


        <main class="grow flex flex-col w-full rounded-md overflow-x-hidden overflow-y-auto">

            <!-- Role -->
            <Role />
            <!-- Tech Stack -->
            <TechStack />

            <section class="flex item-center justify-center mt-10 flex-col p-5">
                <h1 class="text-3xl font-rubik-mono">#About</h1>
                <p class="font-rubik text-xl text-justify mt-5">Hi, my name is <strong>Roxy</strong>. I'm a passionate
                    Full-Stack Web Developer who loves creating
                    modern websites. I
                    recently graduated and have been learning cutting-edge web technologies like Nuxt, Vue, Hono, and
                    Tailwind. In fact, I've been using Vue and Hono extensively in my personal projects.
                </p>

                <p class="flex items-center font-rubik text-lg">
                    I'm currently accepting freelance project, just reach out via <a
                        href="https://mail.google.com/mail/u/0/?to=mercedroxy@gmail.com&fs=1&tf=cm"
                        class="font-rubik group py-2 px-2">
                        <Icon name="i-lucide-mail" size="30"
                            class="group-hover:scale-120 transition-transform duration-150" />
                    </a> and let's build something awesome together!
                </p>
                <button class="bg-red-500 text-white font-rubik w-1/6 p-3 rounded-md hover:opacity-40 transition-all border border-red-500 bg-trans duration-150 hover:scale-90">Download CV</button>

                
            </section>

        </main>


        <SideNav />

    </div>
</template>