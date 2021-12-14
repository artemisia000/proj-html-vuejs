<template>

  <div class="hero">
      <div class="content box2 text" >
          <h1>Drive with Avada</h1>
          <h4 class="w-300" >We offer the finest driving tuition money can buy</h4>
      </div>
      <div class="cart" >
          <div  class="shop boxes2 animated infinite pulse">
              <i class="fas fa-archive box6 demos"></i>
              <p class="box3 f-13" >Demos</p>
          </div>
          <div class="shop boxes2 animated infinite pulse">
              <i class="fas fa-dollar-sign box6"></i>
              <span class="box1 ">39</span>
              <p class="box3 f-13" >On Sale</p>
          </div>
      </div>
  </div>

</template>

<script>

export default {
    name: 'Hero'
}

</script>

<style scoped lang="scss">

.hero{
    width: 100%;
    height: 600px;
    position: relative;  
    background-image: url(../assets/homepage-hero-background.jpg);
    background-size: cover;

    .cart{
        position: fixed;
        right: 20px;
        top: 120px;
        z-index: 3;

    .shop{
        width: 70px;
        height: 70px;
        border-radius: 5px;
        margin-top: 10px;
        text-align: center;
        background-color: #fff;
        text-align: center;
    }
}

        .demos{
            font-size: 30px;
            padding-top: 10px;
        }
        
        span{
            font-size: 35px;
        }
      } 
    
    .text{
        height: 100%;
        flex-direction: column;
        justify-content: center;

        h1{
            font-size: 60px;
        }
    }


</style>