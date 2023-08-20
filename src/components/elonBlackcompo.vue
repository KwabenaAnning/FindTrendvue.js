<script setup>
defineProps(['textElon','image', 'xSign'])
</script>

<template>
 <div class="textElon">
    <img :src="image"/>
    <p>{{textElon}}</p>
    <img :src="xSign"/>
 </div>
</template>

<style scoped>
  .textElon{
    padding: 29px 33px 33px 41px;
    max-width: 341.226px;
    /* transform: rotate(-4deg); */
    background: #181818;
  }
</style>