<template>

<div class="content justify-content-between">
    <div class="card boxes boxes2">
        <img src="../assets/mikehart.jpg" alt="">
        <h4 class="box3 mt-3" >Mike Hart</h4>
        <div class="social">
            <i class="box fab fa-facebook-f"></i>
            <i class="box fab fa-twitter"></i>
            <i class="box fab fa-instagram"></i>
        </div>
        <span class="box mt-3 lh-base w-300 f-13" >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </span>
    </div>
    <div class="card boxes boxes2">
        <img src="../assets/johnsmith.jpg" alt="">
        <h4 class="box3 mt-3" >John Smith</h4>
        <div class="social">
            <i class="box fab fa-facebook-f"></i>
            <i class="box fab fa-twitter"></i>
            <i class="box fab fa-instagram"></i>
        </div>
        <span class="box mt-3 lh-base w-300 f-13" >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </span>
    </div>
    <div class="card boxes boxes2">
        <img src="../assets/angelahart.jpg" alt="">
        <h4 class="box3 mt-3" >Angela Hart</h4>
        <div class="social">
            <i class="box fab fa-facebook-f"></i>
            <i class="box fab fa-twitter"></i>
            <i class="box fab fa-instagram"></i>
        </div>
        <span class="box mt-3 lh-base w-300 f-13" >
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
    width: 318px;
    height: 350px;
    border-radius: 15px;
    border-top: 6px solid #7abc64;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px;
    bottom: -45px;

    img{
        width: 200px;
    }

    .social{
        margin-top: 10px;
        
        i{
            padding: 0 12px;
        }
    }
}

</style>