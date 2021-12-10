<template>
<div class="hero d-flex justify-content-center">
    <div class="content news">
        <div>
            <h1 class="box3" >Latest News</h1>
        </div>
        <div>
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
        <img src="../assets/triangleBottom.png" alt="">
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
        height: 500px;
        background-color: #fff;
        border-top: 6px solid #7799ad;
        border-radius: 10px 10px 0 0;
        position: absolute;
        top: -35px;
        left: 229px;

 
       
    }

    img{
        width: 1050px;
        margin-top: 465px;        
        }

}

</style>