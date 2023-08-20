<script setup>
import ButtonComponent from './ButtonComponent.vue';
import TheNavbar from './TheNavbar.vue';
import elonBlackcompo from './elonBlackcompo.vue';
import twitter from '@/components/images/twitter.png';
import pinterest from '@/components/images/image_96(2).svg'
import fbook from '@/components/images/image_95(1).svg'
import bball from '@/components/images/Rectangle_6(1).svg'
import xSign from '@/components/images/Group_1.svg';
</script>

<template> 
    <div class="Heeero">
        <div>
        <TheNavbar/>
        </div>
        <div class= "heroes">
            <div class="textss">
               <p>Minimize your tabs.</p>
               <p>Find the trends!</p>
            </div>
            <div class="unboldenedtexts">
               <p>Don’t let your computer memories consumes all of those browser tabs. 
                Findtrend  let you gathers all of your favorite website into one place.</p>
            </div>
            <div class="gStart">
               <ButtonComponent class="button" buttonText= "Get started🔥"/>
               <img src="@/components/images/img-hero.svg" alt="" class="imgstack">
            </div>
            <div class="superBlack">
                <elonBlackcompo class="elonMusk" textElon="Cryptopunk-Search" :image="twitter" :xSign="xSign"/>
                <elonBlackcompo class="elonMus"  :image="pinterest" :xSign="xSign" textElon="Popular Design - Search"/>
                <elonBlackcompo class="elonMu" textElon="Product Design - Search" :image="fbook" :xSign="xSign"/>
                <elonBlackcompo class="elonM" textElon="Elon Musk - Search" :image="bball" :xSign="xSign"/>
            </div>
            <!-- <div class="turningTexts">
                <img src="@/components/images/btn-hero-socmed.png" alt="" class="imageUndertext">
            </div> -->
        </div>
    </div>
</template>

<style scoped>
.Heeero{
      background-color: black;
      padding-bottom:99.27px ;
}

.heroes{
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.textss{
    margin: 0 auto;
    color: #FFF;
    text-align: center;
    font-size: 72px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%;
    max-width: 700px;
    margin-top: 110px ;
    margin-bottom: 24px;
}

.unboldenedtexts{
    margin: 0 auto;
    color: #8B8B8B;
    text-align: center;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    height: 54px;
    max-width: 666px;
   
}

.gStart{
    display: flex;
    justify-content: center;
    margin-top: 40px;
    margin-bottom: 111px;
    align-items: center;
    text-align: center;
}
.elonMusk{
    color: white;
    display: flex;
    transform: rotate(-4deg);
    background: linear-gradient(270deg, #181818 53.65%, rgba(24, 24, 24, 0.80) 100%);
}

.elonMus{
    color: white;
    display: flex;
    transform: rotate(2deg);
}

.elonMu{
    color: white;
    display: flex;
    transform: rotate(-2deg);
}

.elonM{
    color: white;
    display: flex;
    transform: rotate(4deg);
}

 .button{
    border-radius: 40px;
    background: #A8FF35;
 }

 .superBlack{
    display: flex;
    margin: 0 auto;
    justify-content: space-around;
   
 }

 @media (max-width:850px) {
    .superBlack{
    display: flex;
    margin: 0 auto;
    justify-content: space-around;
    justify-content: center;
 }
 }

 @media (max-width:789px) {
    .superBlack{
        display: flex;
        flex-direction: column;
        justify-content: center;
        margin: 0 auto;
        padding-bottom: 49.84px;
    }
 }



 @media (max-width:610px) {
    .superBlack{
        display: flex;
        flex-direction: column;
        justify-content: center;
        margin: 0 auto;
        padding-bottom: 49.84px;
    }
 }
 /* .getstarted{
    width: 99.417px;
    height: 69.625px;
    margin: 0 auto;
    display: flex;
    justify-content: center;  
 } */
/* .imgstack{
    width: 99.417px;
    height: 69.625px;
    margin: 0 auto;
    display: flex;
    justify-content: center;      
    
 } */
  
  /* .crypto{
    background: #181818;
    width: 341.226px;
    height: 82px;
    transform: rotate(-4deg);
}

.popDesign{
    background: #181818;
    width: 341.226px;
    height: 82px;
    transform: rotate(2deg);
    };

    .prodDesign{
    background: #181818;
    width: 341.226px;
    height: 82px;
    transform: rotate(-2deg);
    };
     

    .prodDesign{
    background: #181818;
    width: 341.226px;
    height: 82px;
    transform: rotate(-2deg);
    };

    .elon{
        background: #181818;
        width: 341.226px;
        height: 82px;
        transform: rotate(4deg);
    } */

    /* .turningText{
        display: flex;
    } */
 
</style>