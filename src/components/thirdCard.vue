<template>
  <div class="thirdCard">
    <p>Findtrend helps you to increase your productivity and reduce your computer's memory load, <span class="greyBold">an application that can fulfill your daily browsing needs.</span></p>
 </div> 
</template>


<style scoped>
.thirdCard {
    padding: 140px;
    color: #000;
    font-style: normal;
    font-weight: 700;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-size: 64px;
    font-weight: 700;
    line-height: normal;
    /* max-height: 304px; */
    padding: 140px;

} 

.greyBold{
    color: #ADADAD;
    font-size: 64px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}

@media (max-width: 610px) {
    .thirdCard{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: left;
    color: #000;
    font-size: 36px;
    font-weight: 900;
    line-height: normal;
    }


}

</style>