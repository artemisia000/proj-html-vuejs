<template>

<div class="content  justify-content-beetween">
    <div class="card">
        <div class="circle">
            <span class="box fs-1">95%</span>
        </div>
        <span class="f-18 box">PASS RATE</span>
    </div>
    <div class="card">
        <div class="circle">
            <span class="box fs-1" >95%</span>
        </div>
        <span class="f-18 box">PASS RATE</span>
    </div>
    <div class="card">
        <div class="circle">
            <span class="box fs-1" >95%</span>
        </div>
        <span class="f-18 box">PASS RATE</span>
    </div>

</div>
  
</template>

<script>
export default {
    name: 'Percentages'
}
</script>

<style scoped lang="scss">


.card{
    width: 340px;
    height: 400px;
    border-radius: 15px;
    border-top: 6px solid #7abc64;
    justify-content: center;
    align-items: center;
    
    .circle{
        width: 200px;
        height: 200px;
        border: 10px solid #7abc64;
        border-radius: 50%;
        text-align: center;
        line-height: 200px;
    }
    }


</style>