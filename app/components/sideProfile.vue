<script setup lang="ts">

</script>

<template>
    <aside class="sn:w-1/5 gap-4 flex sm:flex-col h-[120px] rounded-md sm:order-1 order-2">
        <section class=" flex justify-center ">
            <img src="https://www.kindpng.com/picc/m/722-7221920_placeholder-profile-image-placeholder-png-transparent-png.png"
                alt="" class="sm:rounded-full rounded-lg aspect-auto sm:p-8 sm:w-3/4 w-[120px]  ">
        </section>

        <section class="sm:p-10 font-rubik-mono flex flex-col sm:gap-6 justify-start items-start text-xl">
            <div class="flex gap-3 justify-between items-center">
                <h1 class="text-md sm:text-lg">ROX-DEV</h1>
            </div>

            <!-- <div class="flex gap-3 justify-between items-center">
                <Icon name="i-lucide-map-pin" size="12"  />
                <p class="font-rubik text-sm sm:text-base">Philippines</p>
            </div> -->

            <div class="flex flex-col gap-3 justify-between items-center">

                <p class="sm:text-lg text-sm text-red-500">Contacts</p>
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
                    <a href="https://ph.linkedin.com/in/merced-roxy-51b193328" class="font-rubik group py-2">
                        <Icon name="i-lucide-link"  size="30"
                            class="group-hover:scale-120 transition-transform duration-150" />
                    </a>
                </div>

            </div>

        </section>
    </aside>
</template>