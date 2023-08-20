<script setup>
  import elonBlackcompo from './elonBlackcompo.vue';
  import findtrend from '@/components/images/Group_16.svg';
  import x_Sign from '@/components/images/Group_1.svg';
</script>
<template>
    <div class="secondCard">
        <div class="head">
            <p>Open new tabs is sh*t </p>
        </div>
        <div class="elon">
            <img src="@/components/images/solutionfordiscover.png" alt="" class="solutionDiscover">
            <elonBlackcompo class="elons" :image="findtrend"  textElon="Findtrend-Elon Musk"  :xSign="x_Sign" />
            <img src="@/components/images/youjustneed.png" alt=""  class="youJustneed">
        </div>
        <div class="textunderElon">
            <p>A solution for your browser tabs and don’t make your device get slower over time. Get ease and faster to discover a trend with just one tab.</p>
        </div>
   </div>
</template>


<style  scoped>
.secondCard{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 60px;
    background: #A8FF35;
    padding: 140px; 
}

.elon{
    display: flex;
    justify-content: center;
    gap: 25px;
    padding: 29px 33px 33px 41px;
 }

.elons{
    color: #FFF;
    text-align: center;
    font-size: 20.806px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    display: flex;
    justify-content: center;
    gap: 25px;
    max-width: 341.226px;
   
}


.head{
    display: flex;
    justify-content: center;
    color: #000;
    text-align: center;
    font-size: 72px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    /* max-height: 86px;
    height: 100%;
    width: 100%;
    max-width: 854px; */
}
.textunderelon{
    display: flex;
    color: #000;
    text-align: center;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
}

@media (max-width: 610px){

    .head{
        display: flex;
        justify-content: center;
        color: #000;
        text-align: center;
        font-size:  36px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
        height: 40px;
    }
    .elon{
           display:flex;
           flex-direction: column-reverse
    };

    .elons{
        display: flex;
        flex-direction: column;
        
    }
       
    .solutionDiscover{
            display: flex;
            align-items: right;
    }

    .youJustneed{
        display: flex;
          align-items: left;
    }

       

    }
</style>