<script setup lang="ts">
</script>

<template>
    <div class="h-screen flex gap-4  bg-slate-950 p-5 overflow-hidden text-white">
        <aside class="w-1/5  rounded-md">
            <section class=" flex justify-center ">
                <img src="https://www.kindpng.com/picc/m/722-7221920_placeholder-profile-image-placeholder-png-transparent-png.png"
                    alt="" class="rounded-full aspect-auto p-8 w-3/4 ">
            </section>

            <section class="p-10 font-rubik-mono flex flex-col gap-6 justify-start items-start text-xl">
                <div class="flex gap-3 justify-between items-center">
                    <h1 class="text-xl">The-FerryMan1</h1>
                </div>

                <div class="flex gap-3 justify-between items-center">
                    <Icon name="i-lucide-map-pin" size="20" />
                    <p class="font-rubik ">Philippines</p>
                </div>

                <div class="flex gap-3 justify-between items-center">
                    <a href="https://github.com/The-FerryMan1" class="font-rubik">
                        <Icon name="i-lucide-github" size="30" />
                    </a>
                    <a href="https://mail.google.com/mail/u/0/?to=mercedroxy@gmail.com&fs=1&tf=cm" class="font-rubik">
                        <Icon name="i-lucide-mail" size="30"  />
                    </a>
                </div>

            </section>

            <section>

            </section>
        </aside>

        <main class="grow  rounded-md ">
            body
        </main>
        <SideNav />

    </div>
</template>