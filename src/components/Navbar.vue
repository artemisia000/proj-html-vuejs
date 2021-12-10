<template>

<div class="navbar">
    <div class="content box2 justify-content-between">
        <div>
            <img src="../assets/avada-drivers-logo-2.png" alt="">
        </div>
        <div class="menu"  >
            <div>
                <a href="">HOME</a>
            </div>
            <div>
                <a href="">ABOUT</a>
            </div>
            <div>
                <a href="">PRICES</a>
            </div>
            <div>
                <a href="">COURSES</a>
            </div>
            <div>
                <a href="">LOCATIONS</a>
            </div>
            <div>
                <a href="">BLOG</a>
            </div>
            <div class="btnAvada btn1">
                <a href="">
                BOOK NOW
                </a>
            </div>
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

    .menu{
        display: flex;
        align-items: center;
      
        div{
            padding: 0 15px;
        }       
    }

    a{
        color: #fff;
        font-size: 12px;
        font-weight: 600;
        text-decoration: none;
    }    
    
}

.btn1{
    width: 120px;
}

</style>