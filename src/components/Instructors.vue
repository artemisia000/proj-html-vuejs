<template>

<div class="content justify-content-between">
    <div class="card">
        <img src="../assets/mikehart.jpg" alt="">
        <h4 class="box3 mt-5" >Mike Hart</h4>
        <div class="social">
            <i class="box fab fa-facebook-f"></i>
            <i class="box fab fa-twitter"></i>
            <i class="box fab fa-instagram"></i>
        </div>
        <span class="box" >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </span>
    </div>
    <div class="card">
        <img src="../assets/mikehart.jpg" alt="">
        <h4 class="box3 mt-5" >John Smith</h4>
        <div class="social">
            <i class="box fab fa-facebook-f"></i>
            <i class="box fab fa-twitter"></i>
            <i class="box fab fa-instagram"></i>
        </div>
        <span class="box" >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </span>
    </div>
    <div class="card">
        <img src="../assets/mikehart.jpg" alt="">
        <h4 class="box3 mt-5" >Angela Hart</h4>
        <div class="social">
            <i class="box fab fa-facebook-f"></i>
            <i class="box fab fa-twitter"></i>
            <i class="box fab fa-instagram"></i>
        </div>
        <span class="box" >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </span>
    </div>

</div>
  

</template>

<script>
export default {
    name: 'Instructors'
}
</script>

<style scoped lang="scss">

.card{
    width: 340px;
    height: 400px;
    border-radius: 15px;
    border-top: 6px solid #7abc64;
    justify-content: center;
    align-items: center;

    img{
        width: 250px;
    }
}

</style>