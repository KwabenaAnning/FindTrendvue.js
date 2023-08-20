<script setup>
import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
    <div class="cardEight">
        <p class="Join">Join us on email for</p>
        <!-- <div class="trendJoin"> -->
            <p class="mTrend">more trending topics</p>
            <ButtonComponent class="button" buttonText="Join Now" />
        <!-- </div> -->
    </div>
</template>

<style scoped>
.cardEight{
    background-color:  #A8FF35;
    padding: 140px;
    display: flex;
    flex-direction: column;

    

}
.Join{
    color: #000;
    text-align: center;
    font-size: 72px;
    font-style: normal;
    font-weight: 900;
   

     /* 80.64px */
}

.mTrend{
    color: #87D322;
    text-align: center;
    font-size: 72px;
    font-style: normal;
    font-weight: 900;
    /* 80.64px */ 
    
}

.joinNow{
    display: flex;
    flex-direction: column;
    justify-self: center;
    text-align: center;
    margin: 0 auto;
    width: 100%;
    width: 180px;
    padding: 16px 32px;
    gap: 10px;
    border-radius: 40px;
    border: none;
}

.button{
    display: flex;
width: 180px;
padding: 16px 32px;
display: flex;
margin: 0 auto;
justify-content: center;
align-items: center;
gap: 10px;
border-radius: 40px;
background: #000;
color: #FFF;
text-align: center;
font-size: 18px;
font-style: normal;
font-weight: 700;
line-height: 140%; /* 25.2px */
}

/* .trendJoin{
    display: flex;
    flex-direction: column;
    gap: 40px;
    justify-content: center;
} */

</style>