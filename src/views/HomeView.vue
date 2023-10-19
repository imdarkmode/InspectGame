<script setup lang="ts"></script>

<template>
  <main>
    <div class="full-center-container">
      <h1>Welcome to the Inspect Game</h1>
      <router-link to="/game" custom v-slot="{ navigate }">
        <button class="light-btn" @click="navigate" role="link">Start</button>
      </router-link>
    </div>
  </main>
</template>

<style scoped lang="sass"></style>
