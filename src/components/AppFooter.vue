/* eslint-disable */
<template>
  <div class="bg-blue-800 dark:bg-gray-200 flex justify-between p-4">
    <div class="text-white dark:text-blue-800 flex items-center">
      <router-link
        to="https://www.google.com/maps/dir/53.5251402,-2.5720833/wigan+library/@53.5346307,-2.636211,13z/data=!3m1!4b1!4m9!4m8!1m1!4e1!1m5!1m1!1s0x487b0f7a87e9050f:0x37fbc44593c758a9!2m2!1d-2.6303!2d53.545529"
        class="hover:bg-white hover:text-blue-800 hover:border-blue-200 hover:border-2 p-2 rounded" target="blank">
        Find us</router-link>
      <router-link to="/"
        class="hover:bg-white hover:text-blue-800 hover:border-blue-200 hover:border-2 p-2 rounded">Gallery</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app-footer'
}
</script>

<style>
</style>