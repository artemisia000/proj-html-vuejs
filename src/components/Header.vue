<template>

<header>
    <GreenNum />

    <Navbar />


</header>
  
</template>

<script>

import GreenNum from '@/components/GreenNum.vue';
import Navbar from '@/components/Navbar.vue';


export default {
    name: 'Header',

    components: {  
        GreenNum,
        Navbar,
    }
}

</script>

<style>

</style>