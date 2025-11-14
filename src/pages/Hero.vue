<script setup lang="ts">



const links = [
    {
        label: 'Get CV',
        icon: 'i-lucide-file-user',
        onclick: async (e: Event) => {
            const link = document.createElement('a')
            link.href = '../../public/resume/Roxy-Villalino-Merced-Resume.pdf'
            link.download = 'roxy_resume.pdf'
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);

        }
    },
    {
        label: 'Projects',
        to: '#projects',
        color: 'neutral',
        variant: 'subtle',
        trailingIcon: 'i-lucide-arrow-right'
    }
]
</script>


<template>
    <UPageHero title="Full-Stack Developer"
        description="Full-Stack Developer with six months of professional experience in a dynamic environment, successfully delivering key features from concept to production deployment. I am proficient in modern architectural principles and committed to building scalable solutions that address real-world challenges."
        :links orientation="horizontal">

        <img src="../assets/img/lazybot.png" alt="App screenshot" class="rounded-lg" />
    </UPageHero>
</template>