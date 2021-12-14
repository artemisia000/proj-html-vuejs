<template>
<div class="hero d-flex justify-content-center">
    <div class="news">
        <div class="latest">
            <h1 class="box3 mt-5 f-35" >Latest News</h1>
        </div>
        <div class="d-flex cards" >
            <div class="card">
                <img src="../assets/choosecar.jpg" alt="">
                <h4 class="mt-3" ><a href="">What Car to Start With?</a></h4>
                <span class="f-11 box" >February 7th, 2019|<span class="box1" >0 Comments</span></span>
                <span class="box f-15 mt-3 w-300">Lorem ipsum dolor sit amet, consectetur adipiscing</span>
            </div>
            <div class="card">
                <img src="../assets/blogspot.jpg" alt="">
                <h4 class="mt-3" ><a href="">Avada Driving School Expanding</a></h4>
                <span class="f-11 box" >February 7th, 2019| <span class="box1" >0 Comments</span></span>
                <span class="box f-15 mt-3 w-300">Lorem ipsum dolor sit amet, consectetur adipiscing</span>
            </div>
        </div>
        <div class="btnAvada button">
            <a href="">MORE FROM THE BLOG</a>
        </div>
    </div>
    <div>
        <img src="../assets/triangleBottom.png" alt=""
        class="triangle">
    </div>
</div>
  
</template>

<script>
export default {
    name: 'Hero3'

}
</script>

<style scoped lang="scss">

.hero{
    width: 100%;
    height: 700px;
    background-image: url(../assets/latestnews-background.jpg);
    background-size: cover;
    position: relative;

    .news{
        width: 970px;
        height: 585px;
        margin: 0 auto;
        background-color: #fff;
        border-top: 6px solid #7799ad;
        border-radius: 10px 10px 0 0;
        position: absolute;
        top: -50px;
        left: 274px;

        .latest{
            width: 970px;
            text-align: center;
        }

        .card{
            width: 400px;
            height: 100%;
            margin: 40px auto;
            text-align: center;
            border: transparent;

            img{
                &:hover{
                    filter: brightness(1.4);
                    transition: filter 1s linear;
                }
            }

            a{
                text-decoration: none;
                color: #7abc64;
                font-size: 20px;
            }  
        }

        .button{
            width: 220px;
            margin: 0 auto;
        }     
    }

    .triangle{
        width: 970px;
        margin-top: 535px; 
        filter: drop-shadow(30px 10px 4px#588281 );       
        }
}

</style>