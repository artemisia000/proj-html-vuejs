<template>
 <div class="content box sectionTop">
     <div class="text">
         <h1 class="box3 my-4 f-35">Get Behind The Wheel</h1>
         <p class="f-18 w-300 mt-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.
         </p>
         <p class="f-13 w-300 mt-4" >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh.
         </p>
     </div>
     <div class="form boxes d-flex align-items-center text-center">
         <h3 class="box1 mt-5" >First Lesson Free!</h3>
         <p class="my-3 mx-5 f-13 w-300" >When you make a block booking with us your first lesson is included free.</p>
         <input type="text"
                placeholder="Your Name*"
                class="f-11">
         <input type="text"
                placeholder="Email"
                class="f-11">
         <input type="text"
                placeholder="Telephone*"
                class="f-11">
        <input type="text"
                placeholder="Location"
                class="f-11">
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
    height: 600px;
    justify-content: space-between;
    position: relative;

    .text{
        width: 450px;
        margin-top: 50px;
        line-height: 30px;
            
    }

    .form{
        width: 450px;
        height: 550px;
        display: flex;
        flex-direction: column;
        background-color: #fff;
        right: 0;
        top: -40px;

        input{
            width: 350px;
            height: 40px;
            color: #d2d1d1;
            border: 1px solid #d2d1d1;
            border-radius: 5px;
            margin: 15px auto;
            padding: 10px;
            background-color: #f7f7f7;
        }
        .btn2{
            width: 215px;
        }
    }

}



</style>