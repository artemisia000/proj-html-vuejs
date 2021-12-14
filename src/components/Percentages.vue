<template>

<div class="content justify-content-between">
    <div class="card boxes">
        <div class="box text-center">
            <div class="percent">
                <svg>
                    <circle cx="50%" cy="50%" r="90" ></circle>
                    <circle cx="50%" cy="50%" r="90" ></circle>               
                </svg>
                <div class="number">
                    <h2 class="f-50 fw-light" >95<span>%</span></h2>
                </div>     
            </div>
            <h2 class="text f-15 box">PASS RATE</h2>
        </div>
    </div>

    <div class="card boxes">
        <div class="box text-center">
            <div class="percent">
                <svg>
                    <circle cx="50%" cy="50%" r="90" ></circle>
                    <circle cx="50%" cy="50%" r="90" ></circle>
                </svg>
                <div class="number">
                    <h2 class="f-50 fw-light" >100<span>%</span></h2>
                </div>     
            </div>
            <h2 class="text f-15 box">REFFERAL RATE</h2>
        </div>
    </div>

    <div class="card boxes">
        <div class="box text-center">
            <div class="percent">
                <svg>
                    <circle cx="50%" cy="50%" r="90" ></circle>
                    <circle cx="50%" cy="50%" r="90" ></circle>
                </svg>
                <div class="number">
                    <h2 class="f-50 fw-light" >  0<span>% </span></h2>
                </div>     
            </div>
            <h2 class="text f-15 box" >ACCIDENT RATE</h2>
        </div>
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

    svg{
        position: relative;
        width: 200px;
        height: 200px;
        z-index: 4;
    }

    svg circle{
        width: 100%;
        height: 100%;
        fill: none;
        stroke: #f6f6f6;
        stroke-width: 12;
        stroke-linecap: round;       
    }

    svg circle:nth-child(2){
        stroke-dasharray: 440;
        stroke-dashoffset: 440;
    }

    .percent:nth-child(1) svg circle:nth-child(2){
        stroke-dashoffset: calc(440 - (440 * 95) / 100);
        stroke: #7abc64;
    }
    .percent:nth-child(2) svg circle:nth-child(2){
        stroke-dashoffset: calc(440 - (440 * 100) / 100);
        stroke: #7abc64;
    }
    .percent:nth-child(3) svg circle:nth-child(2){
        stroke-dashoffset: calc(440 - (440 * 0) / 100);
        stroke: #7abc64;
    }

    .number{
        transform: translate(0px ,-135px);
    }

    }

</style>