<template>
<main>
    <SectionTop />

    <Hero2 />

    <Courses />

    <Percentages />

    <YourInstructors />

    <Instructors />

    <Testimonials />

    <Hero3 />

</main>
  


</template>

<script>

import SectionTop from '@/components/SectionTop.vue';
import Hero2 from '@/components/Hero2.vue';
import Courses from '@/components/Courses.vue';
import Percentages from '@/components/Percentages.vue';
import YourInstructors from '@/components/YourInstructors.vue';
import Instructors from '@/components/Instructors.vue';
import Testimonials from '@/components/Testimonials.vue';
import Hero3 from '@/components/Hero3.vue';

export default {
    name: 'Main',
    components: {
        SectionTop,
        Hero2,
        Courses,
        Percentages,
        YourInstructors,
        Instructors,
        Testimonials,
        Hero3,
    }

}
</script>

<style scoped lang="scss">


</style>