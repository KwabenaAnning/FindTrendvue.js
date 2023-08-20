<script setup>
import ButtonComponent from './ButtonComponent.vue'
defineProps([ 'personal', 'special','Num', 'm', 'li1', 'li2', 'li3', 'li4','li5','li6'])
</script>

<template>
        <div class="cards">
            <h3 class="personal">{{personal}}</h3>
            <p class="special">{{special}}</p>
            <hr>
            <div class="monthLink">
                <p class="numb">{{Num}}<span class="month">{{m}}</span></p>
                <div class="linButton">
                    <ul class="links">
                        <li>{{li1}}</li>
                        <li>{{li2}}</li>
                        <li>{{li3}}</li>
                        <li>{{li4}}</li>
                        <li>{{li5}}</li>
                        <li>{{ li6 }}</li>
                    </ul>
                    <ButtonComponent class="button" buttonText="Start Free Trial"/>  
                </div>
            </div>
        </div>
</template>

<style scoped>

.button{
    display: flex;
    justify-content: center;
    border: none;
    background-color: #A8FF35;
}

.cards{
    border-radius: 16px;
    background: #FAFAFA;
    padding: 32px 32px 24px 32px;
}


.personal{
    color: #000;
    font-size: 36px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%; 
}

.special{
    color: #000;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%; /* 18px */
}

hr{
    margin: 32px;
}

.numb{
    color: #000;
    font-size: 64px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%; /* 64px */
}

.month{
    color: #000;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%; /* 18px */
}

.links{
    color: #000;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%; /* 18px */
    display: flex;
    flex-direction: column;
    gap: 30px;
}

.linButton{
    display: flex;
    flex-direction: column;
    gap: 30px;
}

</style>