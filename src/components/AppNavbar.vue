/* eslint-disable */
<template>
  <div class="bg-blue-800 dark:bg-gray-200 flex justify-between p-4">
    <div class="logo text-white dark:text-blue-800 flex flex-col items-center">
      <p class="text-lg font-bold">Wigan Coders</p>
      <p class="p-0 m-0 text-sm">Meet-up</p>
    </div>
    <div class="text-white dark:text-blue-800 flex items-center">
      <router-link to="/" class="hover:bg-white hover:text-blue-800 hover:border-blue-200 hover:border-2 p-2 rounded">Home</router-link>
      <router-link to="/about" class="hover:bg-white hover:text-blue-800 hover:border-blue-200 hover:border-2 p-2 rounded">About</router-link>
    </div>
  </div>
</template>

<script>
export default {
name: 'app-navbar',


}
</script>

<style>
</style>