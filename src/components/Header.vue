<template>

<header>
    <GreenNum />

    <Navbar />

    <Hero />


</header>
  
</template>

<script>

import GreenNum from '@/components/GreenNum.vue';
import Navbar from '@/components/Navbar.vue';
import Hero from '@/components/Hero.vue';


export default {
    name: 'Header',

    components: {  
        GreenNum,
        Navbar,
        Hero,
    }
}

</script>

<style>

</style>