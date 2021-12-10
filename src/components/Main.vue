<template>
<main>
    <SectionTop />

    <Hero2 />

    <Body />

</main>
  


</template>

<script>

import SectionTop from '@/components/SectionTop.vue';
import Hero2 from '@/components/Hero2.vue';
import Body from '@/components/Body.vue';

export default {
    name: 'Main',
    components: {
        SectionTop,
        Hero2,
        Body,
    }

}
</script>

<style scoped lang="scss">

</style>