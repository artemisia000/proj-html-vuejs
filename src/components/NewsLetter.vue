<template>
<div class="hero" >
    <div class="news">
        <h1 class="box3">Sign up to our Newsletter</h1>
        <input type="text">
        <div class="btnAvada">
            <a href="">SUBSCRIBE</a>
        </div>
        <p class="box f-11" >
           (We do not share your data with anybody, and only use it for its intended purpose)
        </p>
    </div>
</div>

  

</template>

<script>
export default {
    name: 'NewsLetter'

}
</script>

<style scoped lang="scss">

.hero{
    width: 100%;
    height: 320px;
    background-image: url(../assets/newsletter_background.jpg);
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;

    .news{
        width: 500px;
        height: 280px;
        
        
        input{
            width: 100%;
            height: 38px;
            border: 1px solid #e3e3e3;
            border-radius: 3px;
            background-color: #f7f7f7;
        }
    }
}


</style>