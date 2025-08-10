<script setup lang="ts">

</script>

<template>
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

            <div class="flex flex-col gap-3 justify-between items-center">

                <p class="text-lg">Contacts</p>
                <div class="flex justify-start items-start w-full gap-5">
                    <a href="https://github.com/The-FerryMan1" class="font-rubik group py-2 ">
                        <Icon name="i-lucide-github" size="30"
                            class="group-hover:scale-120 transition-transform duration-150" />
                    </a>
                    <a href="https://mail.google.com/mail/u/0/?to=mercedroxy@gmail.com&fs=1&tf=cm"
                        class="font-rubik group py-2">
                        <Icon name="i-lucide-mail" size="30"
                            class="group-hover:scale-120 transition-transform duration-150" />
                    </a>
                </div>

            </div>

        </section>
    </aside>
</template>