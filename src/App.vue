


<template>
  <div class="container">
    <h1>Countdown Timer</h1>
    <label for="timeInput">Please input a timer (1-60 seconds): </label>
    <input type="number" id="timeInput" v-model="timeInput" min="1" max="60" inputmode="numeric"> 
    <button @click="startCountdown">Start Countdown</button>
    <div id="timerDisplay">{{ formattedTime }}</div>
  </div>
</template>