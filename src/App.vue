<template>
  <div
    class="min-h-screen bg-gray-100 py-6 flex flex-col justify-center sm:py-12"
  >
  <div class="relative px-4 py-10 bg-white shadow-lg sm:rounded-3xl sm:p-20">
    <div class="relative py-3 sm:max-w-xl sm:mx-auto">         
      <img alt="Vue logo" src="./assets/logo.png" class="mx-auto" />      
      <HelloWorld msg="Hello Vue 3 + Vite in project vite-03 " />
      <p class="ml-2 text-blue-400">vue3 + tailwind.css</p>
    </div>
   </div> 
  </div>
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>