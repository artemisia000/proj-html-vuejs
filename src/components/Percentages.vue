<template>

<div class="content  justify-content-between">
    <div class="card boxes">
        <div class="circle">
            <span class="box f-50 fw-light">95%</span>
        </div>
        <span class="f-15 box mt-5">PASS RATE</span>
    </div>
    <div class="card boxes">
        <div class="circle">
            <span class="box f-50 fw-light">100%</span>
        </div>
        <span class="f-15 box mt-5">REFFERAL RATE</span>
    </div>
    <div class="card boxes">
        <div class="circle">
            <span class="box f-50 fw-light">0%</span>
        </div>
        <span class="f-15 box mt-5">ACCIDENT RATE</span>
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
    width: 318px;
    height: 350px;
    border-radius: 15px;
    border-top: 6px solid #7abc64;
    justify-content: center;
    align-items: center;
    top: -100px;
    
    .circle{
        width: 200px;
        height: 200px;
        border: 10px solid #7abc64;
        border-radius: 50%;
        text-align: center;
        line-height: 180px;

      }
        
    }
    


</style>