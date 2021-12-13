<template>

<div class="navbar">
    <div class="content box2 justify-content-between">
        <div>
            <img src="../assets/avada-drivers-logo-2.png" alt="">
        </div>
        <div class="menu"  >
            <div class="nav" >
                <a href="">HOME</a>
            </div>
            <div class="nav" >
                <a href="">ABOUT</a>
            </div>
            <div class="nav" >
                <a href="">PRICES</a>
            </div>
            <div class="nav" >
                <a href="">COURSES</a>
                <div class="new">
                    <span>NEW</span>
                </div>
            </div>
            <div class="nav" >
                <a href="">LOCATIONS</a>
            </div>
            <div class="nav" >
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
    height: 110px;
    background-color: rgba(0, 0, 0, 0.2);
    position: absolute;
    z-index: 1;

    img{
        width: 230px;
    }

    .menu{
        display: flex;
        align-items: center;
      
        .nav{
            display: flex;
            align-items: center;
            height: 50px;
            padding: 0 20px;
            border-bottom: 4px solid transparent;
            color: #fff;
            &:hover{
                border-bottom: 4px solid #65a84e;
                color: #65a84e;
            }
        }
           
            .new{
                width: 20px;
                height: 14px;
                background-color: #7abc64;
                border-radius: 2px;
                font-size: 10px;
                font-weight: 600;
                text-align: center;
                margin-left: 5px;
                text-align: center; 
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