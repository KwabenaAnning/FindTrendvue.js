<script setup>
import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
<div class="fifth">
    <div class="fifthCard">
        <div class="headFifth">
            <h2>All platform connect to Findtrend</h2>
        </div>
        <div class="platFormfifth">
            <img src="@/components/images/Rectangle_6(1).svg" alt="">
            <img src="@/components/images/twitter.png" alt="" class="twitter">
            <img src="@/components/images/image_96(2).svg" alt="">
            <img src="@/components/images/image_95(1).svg" alt="">
            <img src="@/components/images/image 113.png" alt="">
        </div>
        <img src="@/components/images/platform.png" alt="" class="platform">
        <img src="@/components/images/tweet 1.png" alt="" class="tweet1">
        <img src="@/components/images/tweet 2.png" alt="" class="tweet2">
        <img src="@/components/images/tweet 3.png" alt="" class="tweet3">
    </div>
    <ButtonComponent class="button" buttonText= "View More Trend"/>
</div>
</template>


<style scoped>
.fifth{
    padding: 140px 172px;
   }
   .fifthCard{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 40px;
   }

.headFifth{
    display: flex;
    justify-content: center;
    color: #000;
    text-align: center;
    font-size: 64px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;}
    

.platFormfifth{
    display: none;
}

.twitter{
    border-radius: 8px;
    background: #A8FF35;
}

.button{
    color: #FFF;
    display: flex;
    margin: 0 auto;
    text-align: center;
    font-size: 18px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%; /* 25.2px */
    padding: 16px 32px;
    border-radius: 40px;
    background: #000;
    margin-top: 80px;
}


   @media (max-width: 610px) { 
    .mobileview{
    display: grid;
    grid-template-columns: 1fr 1fr;
   }

   .platform{
    display: none;
   }

   .platFormfifth {
    display: flex;
    justify-content: space-between;
    justify-content: center;
    gap: 49px;

   }

}
   
</style>