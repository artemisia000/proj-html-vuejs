<template>

<footer>

    <NewsLetter />

    <Contact />

    <Social />

</footer>
  
</template>

<script>
import NewsLetter from '@/components/NewsLetter.vue';
import Contact from '@/components/Contact.vue';
import Social from '@/components/Social.vue';


export default {
    name: 'Footer',

    components:{
        NewsLetter,
        Contact,
        Social,
    }
}
</script>

<style>

</style>