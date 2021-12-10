<template>
 <div class="content box sectionTop">
     <div class="text">
         <h1 class="box3 my-5" >Get Behind The Wheel</h1>
         <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.
         </p>
         <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh.
         </p>
     </div>
     <div class="form d-flex align-items-center text-center">
         <h3 class="box1 m-5" >First Lesson Free!</h3>
         <p class="mt-3 mx-3" >When you make a block booking with us your first lesson is included free.</p>
         <input type="text"
                placeholder="Your Name*">
         <input type="text"
                placeholder="Email">
         <input type="text"
                placeholder="Telephone*">
        <input type="text"
                placeholder="Location">
        <div class="btnAvada btn2 mt-3">
            <a href="">REQUEST A CALLBACK</a>
        </div>        
     </div>
   
 </div>
  

</template>

<script>
export default {
    name: 'SectionTop'

}
</script>

<style scoped lang="scss" >

.sectionTop{
    height: 670px;
    justify-content: space-between;
    position: relative;

    .text{
        width: 540px;     
    }

    .form{
        width: 540px;
        height: 650px;
        display: flex;
        flex-direction: column;
        background-color: #fff;
        border-radius: 15px;
        position: absolute;
        right: 0;
        top: -60px;

        input{
            width: 450px;
            height: 50px;
            color: #d2d1d1;
            border-radius: 1px solid #d2d1d1;
            border-radius: 5px;
            margin: 20px auto;
        }
        .btn2{
            width: 215px;
        }
    }

}



</style>