<script setup>
defineProps(['sponsors'])
</script>

<template>
<div class="img">
  <img :src="sponsors">
</div>
</template>

<style>
 .img{
    border-radius: 8px;
    background: #F5F5F5;
    width: 266px;
    height: 120px;
 }
</style>