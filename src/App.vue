<script setup>
import HeroSection from './components/HeroSection.vue';
import secondCard from './components/secondCard.vue';
import thirdCard from './components/thirdCard.vue';
import fourthCard from './components/fourthCard.vue';
import fifthcard from './components/fifthcard.vue';
import MydealsCompo from './components/mydealsCompo.vue';
import eightCard from './components/eightCard.vue';
import footerCompo from './components/footerCompo.vue';


</script>

<template>
  <header>
    <div>
      <HeroSection/>
      <secondCard/>
      <thirdCard/>
      <fourthCard/>
      <fifthcard/>
      <div class="myDealssixth"> 
        <div class="headers">
          <p class="heads">Get your best deal</p>
          <div class="textunderdeals">
              <span class="span">Monthly</span>
              <img src="@/components/images/clickcheck.png" alt=""/>
              <p class="yearly">yearly</p>
              <img src="@/components/images/save10.png" alt="">
          </div> 
        </div>
        <div class="mydealsComp">
          <MydealsCompo  personal="Personal" special="Special first packet for all" Num="$8" m="/month" li1="Up to 5 page each group" 
            li2="Up to 10 group page" li3="5 Days group page saved"/>

            <MydealsCompo
            personal="Regular" special="Recommended for personal pro" Num="$20" m="month" li1="Up to 15 page each group" 
            li2="Download page up to 20 page" li3="Up to 10 group page" li4="15 Days group page saved"/>

            <MydealsCompo 
            personal="Premium" special="Packet for Startup & Company" Num="$48" m="month" li1="Unlimited group pages" 
            li2="Unlimited download page" li3="Unlimited page each group" li4="Customize sorting group pages"
            li5="Customize group page name" li6="30 Days group page saved"/>
        </div>
      </div>
      <eightCard/>
      <footerCompo/>
    </div>
  </header>
</template>


<style scoped>
            

.myDealssixth{
    display: flex;
    flex-direction: column;
    background-color: black;
    padding: 140px;
    gap: 40px;
}

.textunderdeals{
    display: flex;
    margin: o auto;
    justify-content: center;
}
.headers{
  display: flex;
  flex-direction: column;
  gap: 40px;
}
.heads{
    color: #FFF;
    text-align: center;
    font-family: Effra;
    font-size: 64px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}

.span{
    color: #FFF;
    font-family: Inter;
    font-size: 24px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
}

img{
    width: 104px;
    height: 52px;
}


.yearly{
    color: #F5F5F5;
    font-family: Inter;
    font-size: 24px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    opacity: 0.5;
}

.monthLink{
    display: flex;
    flex-direction: column;
    gap: 35px;
}

.mydealsComp{
  display: flex;
  gap: 40px;
  justify-content: center;
}



@media (max-width:610px) {
    .myDealssixth{
        display: flex;
        flex-direction: column;  
    }

  .mydealsComp{
    display: flex;
    flex-direction: column;
    gap: 40px;
    justify-content: center;
}

}


</style> 




<!-- header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} -->