<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <HelloWorld msg="Hey, This Healthmate Chatbot" />
  <br>
  <h1>HEALTHMATE</h1>
  <img src="https://static.wixstatic.com/media/13baa1_39ee18a0e06d41088d4330ecae68f6eb~mv2.png" alt="Healthmate Image" class="healthmate-image" />
  <p>Click in the right bottom to begin your health checkup</p>
  <p>Made By Vanshita Sabnani</p>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
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
