<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <HelloWorld msg="Hey, This Healthmate Chatbot" />
  <br>
  <h1>HEALTHMATE</h1>
  
  <!-- Logo -->
  <img src="https://static.wixstatic.com/media/13baa1_51ff3d0e63a44a5b84d29d6def374680~mv2.png" alt="Healthmate Logo" class="logo" />
  
  <!-- Contact and Address -->
  <div class="top-info">
    <p class="address">Healthmate Hospital, Khandwa</p>
    <p class="contact">Contact No. 1234567890</p>
  </div>
  
  <img src="https://static.wixstatic.com/media/13baa1_39ee18a0e06d41088d4330ecae68f6eb~mv2.png" alt="Healthmate Image" class="healthmate-image" />
  
  <p>Click in the right bottom to begin your health checkup</p>
  <p>Made By Vanshita Sabnani</p>
</template>

<style scoped>
body {
  background: linear-gradient(to bottom, #ffffff, #a0c4ff);
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

.logo {
  height: 5em;
  position: absolute;
  top: 10px;
  right: 10px;
}

.top-info {
  position: absolute;
  top: 10px;
  left: 10px;
}

.address {
  margin: 0;
  font-size: 0.9em;
}

.contact {
  margin: 0;
  font-size: 0.9em;
}

h1 {
  text-align: center;
  margin: 2em 0;
}

.healthmate-image {
  display: block;
  margin: 0 auto;
  max-width: 100%;
  height: auto;
}
</style>
