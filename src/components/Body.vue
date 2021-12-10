<template>
<div class="body">
    <div class="content ">
        <div class="tab boxes text-center">
            <h1>Courses</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.</p>
            <div class="btnAvada button">
                COURSE INFORMATION
            </div>
        </div>
        <div class="courses">
            <div class="car">
                <img src="../assets/courses.jpg" alt="">
                    <h3>Pass Plus</h3>
                <div class="btnAviat">
                    <a href="">LEARN MORE</a>
                </div>       
            </div>
            <div class="car">
                <img src="../assets/intensive.jpg" alt="">
                    <h3>Pass Plus</h3>
                <div class="btnAviat">
                    <a href="">LEARN MORE</a>
                </div>       
            </div>
            <div class="car">
                <img src="../assets/instructor.jpg" alt="">
                    <h3>Pass Plus</h3>
                <div class="btnAviat">
                    <a href="">LEARN MORE</a>
                </div>       
            </div>
        </div>
    </div>


</div>
  
</template>

<script>
export default {
    name: 'Body'

}
</script>

<style scoped lang="scss">

.body{
    width: 100%;
    height: 550px;
    background-image: url(../assets/promise-background.jpg);
    background-size: cover;
    position: relative;

    .tab{
        width: 420px;
        height: 420px;
        background-color: #fff;
        top: -30px;

        .button{
            width: 220px;
        }           
    }

    .car{
        width: 160px;
        height: 300px;
        
    }






}

</style>