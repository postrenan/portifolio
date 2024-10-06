<template>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    </head>
    <Header/>
    <Projects/>
    <About/>
    <Footer/>
</template>

<script setup lang="ts">
import About from '~/components/about.vue';
import Footer from '~/components/footer.vue';
import Header from '~/components/header.vue';
import Projects from '~/components/projects.vue';
</script>