<template>
<div class="hero">
    <div class="content contact">

        <div class="card pe-4">
            <img src="../assets/avada-drivers-logo-2.png" alt="">
            <p class="f-11 box lh-lg mt-3" >Avada Driving School is the right choice for experienced drivers looking for a refresher course, or the brand new driver wanting to pass first time.</p>
        </div> 

        <div class="card pe-4">
            <h5 class="f-15 box2 mb-3" >CONTACT DETAILS</h5>
            <div>
                <i class="fas fa-home box5"></i>
                <span class="f-11 box" >12345 North Main Street,<br>
                       <span class="ms-3" >New York, NY 555555</span>
                </span>
            </div>

            <div>
                <i class="fas fa-phone box5"></i>
                <span class="f-11 box" >
                    1.800.555.6789
                </span>
            </div>

            <div>
                <i class="far fa-envelope box5"></i>
                <span class="f-11 box" >
                    info@your-domain.com
                </span>
            </div>

            <div>
                <i class="fas fa-link box5"></i>
                <span class="f-11 box" >
                    Theme-Fusion.com
                </span>
            </div>      
        </div>

        <div class="card pe-4">
            <h5 class="f-15 box2 mb-3" >COURSES</h5>
            <div>
                <i class="far fa-arrow-alt-circle-right box1 "></i>
                <span>
                    <a class="box1 f-15" href="">Pass Plus</a>
                </span>
            </div>

            <div>
                <i class="far fa-arrow-alt-circle-right box1"></i>
                <span>
                    <a class="box1 f-15" href="">Intensive Course</a>
                </span>
            </div>

            <div>
                <i class="far fa-arrow-alt-circle-right box1"></i>
                <span>
                    <a class="box1 f-15" href="">Automatic</a>
                </span>
            </div>

            <div>
                <i class="far fa-arrow-alt-circle-right box1"></i>
                <span>
                    <a class="box1 f-15" href="">Instructor Training</a>
                </span>
            </div>
        </div> 

        <div class="card">
            <img src="../assets/grid1.png" alt="">
            <div class="btnAvada mt-4 button">
                <a href="">BOOK NOW</a>
            </div>
        </div>
    </div>
</div>

</template>

<script>

export default {
    name: 'Contact'
}

</script>

<style scoped lang="scss">

.hero{
    width: 100%;
    height: 380px;
    background-image: url(../assets/footer-background-color.jpg);
    background-size: cover;
    
.card{
    width: calc(100% /4);
    height: 350px;
    background-color: transparent;
    border: transparent;
    padding-top: 50px;

    span{
        padding-left: 10px;
        line-height: 35px;
    }

    a{
        text-decoration: none;
        font-size: 15px;
        &:hover{
            color: #7abc64;
        }    
    }

    .button{
        width: 140px;
        margin: 0 auto;
    }  
  }
}


</style>