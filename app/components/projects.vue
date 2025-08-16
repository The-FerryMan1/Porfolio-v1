<script setup lang="ts">

</script>

<template>
    <section class="p-5 mt-10 mb-10">
        <h1 id="Projects" class="text-3xl font-rubik-mono mb-5">#Projects</h1>


        <!-- card container -->
        <section class="sm:grid-cols-2 grid-cols-1 grid gap-1">
            <!-- card -->
            <div class="flex flex-col gap-2 rounded-xl border border-white/80">
                <img src="../assets/img/vitapulse.png" alt="" class="size-full rounded-xl">

                <div class="p-4 font-rubik ">
                    <p class="font-bold">VitaPulse</p>
                    <p class="font-semibold ">Commissioned</p>
                    <div class="flex mt-5 gap-3">
                        <img src="../assets/img/hono.svg" alt="hono logo" class="object-contain size-7">
                        <img src="../assets/img/tailwindcss.svg" alt="tailwindCSS logo"
                            class="object-contain size-7">
                        <img src="../assets/img/vue.svg" alt="Vue logo" class="object-contain size-7">
                    </div>
                    <p class="mt-4">
                        Vitapulse is a web app where user can monitor their blood pressure and pulse rate. The data
                        is collected from Google Sheet, which recieves input from an ESP32 device. Vitapulse retrieves
                        those data and present it through visuals such as graphs, gives alerts to users, and offering
                        real-time updates.


                    </p>
                </div>
            </div>

        </section>
    </section>
</template>
