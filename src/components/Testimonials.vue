<template>
<div class="hero">
    <div class="testimonials">
        <h1 class="box3" >Testimonials</h1>
        <p class="box" >Here’s what our happy drivers had to say about our services:</p>
        <div class="image">
            <img src="../assets/testimonial-kate.png" alt="">
        </div>
        <p class="box coursive" >Avada Driving School really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
        <p class="box" >Sophia Jones</p>

    </div>
</div>

</template>

<script>
export default {
    name: 'Testimonials'
}
</script>

<style scoped lang="scss">

.hero{
    width: 100%;
    height: 870px;
    background-image: url(../assets/testimonial-background.jpg);
    background-size: cover;
    text-align: center;

    .testimonials{
        padding-top: 300px;
    }
    
    img{
        width: 150px;
        margin: 30px 0;
    }

    .coursive{
        font-family: 'Cabin', sans-serif;
        font-family: 'Cabin Sketch', cursive;
        font-family: 'Outfit', sans-serif;
        font-family: 'Readex Pro', sans-serif;
        font-family: 'Work Sans', sans-serif;
    }


}

</style>