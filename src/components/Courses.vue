<template>

<div class="body">
    <div class="content cars">
        <div class="tab boxes text-center boxes2">
            <img src="../assets/new-corner.jpg" alt=""
                 class="new"
                 >
            <h1 class="box3 mt-5 f-35" >Courses</h1>
            <p class="box m-3 lh-lg w-300 f-13" >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.</p>
            <div class="btnAvada button">
                <a href="">COURSE INFORMATION</a>
            </div>
        </div>

        <div class="courses">
            <div class="car">
                <img src="../assets/courses.jpg" alt="">
                    <h3 class="box4 mt-3 f-18" >Pass Plus</h3>
                <div class="btnAviat">
                    <a href="">LEARN MORE</a>
                </div>       
            </div>

            <div class="car ">
                <img src="../assets/intensive.jpg" alt="">
                    <h3 class="box4 mt-3 f-18" >Intensive Course</h3>
                <div class="btnAviat">
                    <a href="">LEARN MORE</a>
                </div>       
            </div>

            <div class="car ">
                <img src="../assets/instructor.jpg" alt="">
                    <h3 class="box4 mt-3 f-18" >Instructors</h3>
                <div class="btnAviat f-13">
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
        height: 350px;
        background-color: #fff;
        top: -30px;
        position: relative;

        .button{
            width: 190px;
            margin: 40px auto;
        }
        
        .new{
            width: 50px;
            position: absolute;
            left: 0;
            border-radius: 13px 0 0 0;
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
            &:hover{
                filter: brightness(1.5);
                transition: filter 1s ease;
            }
        }

    .btnAviat{
        width: 120px;
        margin: 15px auto;
        }
    }
  }
}

</style>