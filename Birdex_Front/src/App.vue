<template>
    <NavBar />
    <div class="bird">
    <img src="./assets/oiseau.jpg" alt="" class="birdImg">
    <div class="birdPlace">
      <h1 class="title">Mésange bleue</h1>
      <span>Coreze</span>

    </div>
    </div>
    <BirdMap />

</template>

<script setup>
import NavBar from './components/NavBar.vue'
import BirdMap from './components/BirdMap.vue'

</script>

<style>
  .birdPlace{
    position: absolute;
    display: block;
    bottom: 40px;
    padding: 20px;
    color:rgb(255, 255, 255);
  }
  .title{
    font-size: 30px;
    font-weight: bold;
  }
  .bird
  { margin-top:20px;
    margin-bottom: 20px;
    width:100vw;
    height: 100vw;
  }
  .birdImg{
  
    width: 100vw;
    height: 100vw;
    object-fit: cover;
  }
</style>


