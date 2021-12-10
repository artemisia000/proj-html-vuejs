<template>

   <div class="greenNum">
       <div class="content box">
            <div class="f-11" >
                We Have a 95% Successfull Pass Rate!
            </div>
            <div class="f-11" >
                <i class="fa-solid fa-phone-flip"></i>
                Give us a call to book your tuition! 1-800-555-555
            </div>
       </div>
   </div>
  
</template>

<script>
export default {
    name: 'GreenNum'
}
</script>

<style scoped lang="scss">

.greenNum{
    width: 100%;
    height: 40px;
    background-color: #484848;
    display: flex;
}

.box{
    justify-content: space-between;
    line-height: 40px;

}

</style>