<template>
<div class="hero">
    <div class="content box2 hero2">
        <div class="text">
            <h1>Start Learning to Drive Today</h1>
            <p>Give us a call to schedule your first driving lesson</p>
        </div>
        <div class="phone">
            <i class="fa-solid fa-phone-flip"></i>
            <span>1-800-555-555</span>
        </div>
    </div>
</div>
  

</template>

<script>
export default {
    name: 'Hero2'
}
</script>

<style scoped lang="scss">

.hero{
    height: 240px;
    background-image: url(../assets/horizontal-cta-background.jpg);
    background-size: cover;
    
    .hero2{
        justify-content: space-between;   
       
    }
}

</style>