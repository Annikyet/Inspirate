<template>
  <main class="flex flex-col">
    <div class="flex h-[20vh]">
      <div class="w-[20vw]"></div>
      <div class="w-[60vw]"></div>
      <div class="w-[20vw]"><Weather /></div>
    </div>
    <div class="flex h-[60vh]">
      <div class="w-[20vw]"></div>
      <div class="w-[60vw] flex-col justify-center">
        <div class="h-[20vh]"></div>
      </div>
      <div class="w-[20vw]"></div>
    </div>
    <div class="flex h-[20vh]">
      <div class="w-[20vw]"></div>
      <div class="w-[60vw]"></div>
      <div class="w-[20vw]"></div>
    </div>
  </main>
</template>

<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Weather from './components/Weather.vue'
</script>

<style scoped>
  div {
    border-color: black;
    border-style: solid;
    border-width: 2px;
  }
</style>
