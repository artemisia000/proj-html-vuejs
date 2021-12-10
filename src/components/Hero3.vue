<template>
<div class="hero d-flex justify-content-center">
    <div class="news">
        <div class="latest">
            <h1 class="box3" >Latest News</h1>
        </div>
        <div class="d-flex" >
            <div class="card">
                <img src="../assets/choosecar.jpg" alt="">
                <h4>gdhdjdkd</h4>
                <span>djdjdkd</span>
                <span>ddkdkdkd</span>
            </div>
            <div class="card">
                <img src="../assets/blogspot.jpg" alt="">
                <h4>gdhdjdkd</h4>
                <span>djdjdkd</span>
                <span>ddkdkdkd</span>
            </div>
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
    height: 600px;
    background-image: url(../assets/latestnews-background.jpg);
    background-size: cover;
    position: relative;

    .news{
        width: 970px;
        height: 500px;
        margin: 0 auto;
        background-color: #fff;
        border-top: 6px solid #7799ad;
        border-radius: 10px 10px 0 0;
        position: absolute;
        top: -35px;
        left: 269px;

        .latest{
            width: 970px;
            text-align: center;
        }

        .card{
            width: 400px;
            height: 100%;
        }
       
    }

    .triangle{
        width: 970px;
        margin-top: 465px;        
        }

}

</style>