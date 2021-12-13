<template>
<footer>
    <div class="content foot">

        <div>
            <p class="box f-11" >&copy;Copyright 2012 - 2021 | Avada Theme by <span class="box1" >ThemeFusion</span> | All Rights Reserved | Powered by <span class="box1" >WordPress</span>
            </p>
        </div>

        <div class="social" >
            <a href=""><i class="fab fa-facebook-f"></i></a>
            <a href=""><i class="fab fa-twitter"></i></a>
            <a href=""><i class="fab fa-youtube"></i></a>
            <a href=""><i class="fab fa-instagram"></i></a>
        </div>
        
    </div>

</footer>
  
</template>

<script>
export default {
    name: 'Social'
}
</script>

<style scoped lang="scss" >

footer{
    width: 100%;
    height: 120px;
    background-color: #1c1d1e;

    .foot{
        height: 120px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .social{
        display: flex;
     
        a{
            width: 11px;
            color: #fff;
            padding: 0 16px;
            margin:auto;
        }   
    }
}

</style>