<template>
<div class="body">
    <div class="content cars">
        <div class="tab boxes text-center">
            <h1 class="box3 my-5" >Courses</h1>
            <p class="box mx-3 lh-base" >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.</p>
            <div class="btnAvada button">
                <a href="">COURSE INFORMATION</a>
            </div>
        </div>
        <div class="courses">
            <div class="car">
                <img src="../assets/courses.jpg" alt="">
                    <h3 class="box4 mt-3 f-20" >Pass Plus</h3>
                <div class="btnAviat">
                    <a href="">LEARN MORE</a>
                </div>       
            </div>
            <div class="car ">
                <img src="../assets/intensive.jpg" alt="">
                    <h3 class="box4 mt-3 f-20" >Intensive Course</h3>
                <div class="btnAviat">
                    <a href="">LEARN MORE</a>
                </div>       
            </div>
            <div class="car ">
                <img src="../assets/instructor.jpg" alt="">
                    <h3 class="box4 mt-3 f-20" >Instructors</h3>
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
    name: 'Courses'

}
</script>

<style scoped lang="scss">

.body{
    width: 100%;
    height: 550px;
    background-image: url(../assets/promise-background.jpg);
    background-size: cover;

    .cars{
        position: relative;
    }
 

    .tab{
        width: 330px;
        height: 330px;
        background-color: #fff;
        top: -30px;

        .button{
            width: 220px;
        }           
    }

    .courses{
        display: flex;
        position: absolute;
        right:0 ;

    .car{
        height: 160px;
        text-align: center;
        margin-top: 80px;
        margin-left: 40px;

        img{
            width: 160px;
        }

    .btnAviat{
        width: 125px;
        }
 
    }


    }

}

</style>