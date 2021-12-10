<template>
<main>
    <SectionTop />

    <Hero2 />

    <Courses />

    <Percentages />

</main>
  


</template>

<script>

import SectionTop from '@/components/SectionTop.vue';
import Hero2 from '@/components/Hero2.vue';
import Courses from '@/components/Courses.vue';
import Percentages from '@/components/Percentages.vue';

export default {
    name: 'Main',
    components: {
        SectionTop,
        Hero2,
        Courses,
        Percentages,
    }

}
</script>

<style scoped lang="scss">


</style>