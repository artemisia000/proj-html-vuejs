<template>
<div class="hero">
    <div class="content box2 hero2">
        <div class="text">
            <h1>Start Learning to Drive Today</h1>
            <p>Give us a call to schedule your first driving lesson</p>
        </div>
        <div class="f-35 w-300">
            <i class="fa-solid fa-phone-flip m-3"></i>
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
        height: 100%;
        justify-content: space-between;
        align-items: center; 
    }

    
}

</style>