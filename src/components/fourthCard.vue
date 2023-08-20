<script setup>
import sponsorsCompo from './sponsorsCompo.vue';
import microsoft from '@/components/images/microsoft.png';
import allianz from '@/components/images/allianz.png';
import upwork from '@/components/images/upwork.png'
import verizon from '@/components/images/image 122.png';
import airtable from '@/components/images/image 117.png';
import algolia from '@/components/images/image 118.png'
import carrera from '@/components/images/image 120.png';
import bonanza from '@/components/images/image 124.png';
import Grab from '@/components/images/image 125.png'
import magento from '@/components/images/image 126.png';
import suzuki from '@/components/images/image 127.png';
import expedia from '@/components/images/image 129.png'
import Heineken from '@/components/images/image 130.png';
import Wetransfer from '@/components/images/image 132.png';
import coinbase from '@/components/images/image 133.png'
import airtable2 from '@/components/images/image 117.png'
</script>


<template>
<div class="fourthCard">
  <div class="headOfcard4">
      <p>Findtrend make +1000 Startup grow</p>
  </div>
  <!-- <div class="brands">
      <img src="@/components/images/Brands.png" alt="">
  </div> -->
  <div class="sponsoRS">
    <sponsorsCompo class="sponsors" :sponsors="microsoft"/>
    <sponsorsCompo class="sponsors" :sponsors="allianz"/>
    <sponsorsCompo class="sponsors" :sponsors="upwork"/>
    <sponsorsCompo class="sponsors" :sponsors="verizon"/>
    <sponsorsCompo class="sponsors" :sponsors="airtable"/>
    <sponsorsCompo class="sponsors" :sponsors="algolia"/>
    <sponsorsCompo class="sponsors" :sponsors="carrera"/>
    <sponsorsCompo class="sponsors" :sponsors="bonanza"/>
    <sponsorsCompo class="sponsors" :sponsors="Grab"/>
    <sponsorsCompo class="sponsors" :sponsors="magento"/>
    <sponsorsCompo class="sponsors" :sponsors="suzuki"/>
    <sponsorsCompo class="sponsors" :sponsors="expedia"/>
    <sponsorsCompo class="sponsors" :sponsors="Heineken"/>
    <sponsorsCompo class="sponsors" :sponsors="Wetransfer"/>
    <sponsorsCompo class="sponsors" :sponsors="coinbase"/>
    <sponsorsCompo class="sponsors" :sponsors="airtable2"/>
  </div>
  <!-- <div class="mobileview">
     <img src="@/components/images/microsoft.png" alt="">
    <img src="@/components/images/allianz.png" alt="">
    <img src="@/components/images/upwork.png" alt="">
    <img src="@/components/images/image 122.png" alt="">
    <img src="@/components/images/image 117.png" alt="">
    <img src="@/components/images/image 118.png" alt="">
    <img src="@/components/images/image 120.png" alt="">
    <img src="@/components/images/image 124.png" alt="">
    <img src="@/components/images/image 125.png" alt="">
    <img src="@/components/images/image 126.png" alt="">
    <img src="@/components/images/image 127.png" alt="">
    <img src="@/components/images/image 129.png" alt="">
    <img src="@/components/images/image 130.png" alt="">
    <img src="@/components/images/image 132.png" alt="">
    <img src="@/components/images/image 133.png" alt="">
    <img src="@/components/images/image 117.png" alt=""> 
  </div>   -->
</div>
</template>


<style scoped>
.fourthCard{
  padding: 140px 140px 0px 140px;
  display: flex;
  flex-direction: column;
  column-gap: 80px;
}

.headOfcard4{
    display: flex;
    flex-direction: column;
    color: #000;
    text-align: center;
    font-size: 64px;
    font-style:normal;
    font-weight: 700;
    line-height: normal;
}

.sponsoRS{
  display: grid;
  padding: 40px 38px;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  justify-content: space-evenly; 
  gap: 10px;
  border-radius: 8px;
  margin-top: 80px;
  text-align: center;
 justify-content: center;
 
}

.sponsors{
  align-items: center;
  text-align: center;
  align-content: center;
  padding: 24px 34px;
  max-width: 162px;
  max-height: 74px;
}

/* .brands{
 display: flex;
 flex-direction: column;
 justify-content: center;
} */

@media (max-width:610px ){
  .sponsoRS{
   display: grid; 
   grid-template-columns: 1fr 1fr;
   align-content: center;
   justify-content: center;
}
}
</style>