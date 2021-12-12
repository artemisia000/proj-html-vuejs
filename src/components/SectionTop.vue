<template>
 <div class="content box sectionTop">
     <div class="text">
         <h1 class="box3 my-4" >Get Behind The Wheel</h1>
         <p class="f-20 lh-lg" >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.
         </p>
         <p class="f-15  lh-base" >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper. Fusce et ultrices libero, at suscipit lacus. Sed vitae fringilla nibh.
         </p>
     </div>
     <div class="form boxes d-flex align-items-center text-center">
         <h3 class="box1 m-3" >First Lesson Free!</h3>
         <p class="mt-3 mx-3 f-15" >When you make a block booking with us your first lesson is included free.</p>
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
            
    }

    .form{
        width: 450px;
        height: 500px;
        display: flex;
        flex-direction: column;
        background-color: #fff;
        right: 0;
        top: -40px;

        input{
            width: 300px;
            height: 35px;
            color: #d2d1d1;
            border: 1px solid #d2d1d1;
            border-radius: 5px;
            margin: 15px auto;
        }
        .btn2{
            width: 215px;
        }
    }

}



</style>