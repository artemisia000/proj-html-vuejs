<template>

<div class="navbar">
    <div class="container-md box2">
        <img src="../assets/avada-drivers-logo-2.png" alt="">
        <div class="">
            <a href="">HOME</a>
        </div>
        <div class="div">
            <a href="">ABOUT</a>
        </div>
        <div class="div">
            <a href="">PRICES</a>
        </div>
        <div class="div">
            <a href="">COURSES</a>
        </div>
        <div class="div">
            <a href="">LOCATIONS</a>
        </div>
        <div class="div">
            <a href="">BLOG</a>
        </div>
        <div class="btnAvada btn1">
            <a href="">
                BOOK NOW
            </a>
        </div>
        
        

    </div>

</div>

</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped lang="scss">

.navbar{
    width: 100%;
    height: 120px;
    background-color: rgba(0, 0, 0, 0.2);
    position: absolute;
    z-index: 1;

    a{
        color: #fff;
        text-decoration: none;
    }  
}

.btn1{
    width: 120px;
}

</style>