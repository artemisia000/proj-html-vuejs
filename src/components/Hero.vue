<template>

  <div class="hero">
      <div class="content box2 text" >
          <h1>Drive with Avada</h1>
          <h4>We offer the finest driving tuition money can buy</h4>
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
    
    
    .text{
        flex-direction: column;
        
        
        
    }
}

</style>