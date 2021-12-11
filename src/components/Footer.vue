<template>
<footer>

    <NewsLetter />

    <Contact />


</footer>
  


</template>

<script>
import NewsLetter from '@/components/NewsLetter.vue';
import Contact from '@/components/Contact.vue';


export default {
    name: 'Footer',

    components:{
        NewsLetter,
        Contact,
    }
}
</script>

<style>

</style>