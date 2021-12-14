<template>

<div class="hero">
    <div class="testimonials">
        <h1 class="box3 f-35">Testimonials</h1>
        <p class="box mt-3 w-300 f-18" >Here’s what our happy drivers had to say about our services:</p>
        <div class="image">
            <img src="../assets/testimonial-kate.png" alt="">
        </div>
        <p class="box coursive" >Avada Driving School really helped build my confidence behind the wheel and with driving in general, and they got me a first time pass! Highly recommended.</p>
        <p class="box my-4" >Sophia Jones</p>
        <div>
            <i class="fas fa-circle"></i>
            <i class="far fa-circle"></i>
            <i class="far fa-circle"></i>
            <i class="far fa-circle"></i>
            <i class="far fa-circle"></i>
        </div>
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
    height: 780px;
    background-image: url(../assets/testimonial-background.jpg);
    background-size: cover;
    display: flex;
    justify-content: center;

    .testimonials{
        width: 650px;
        padding-top: 150px;
        text-align: center;

        i{
            font-size: 10px;
            color: #929aa3;
            padding: 20px 5px;
        }
    }
    
    img{
        width: 150px;
        margin: 40px 0;
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