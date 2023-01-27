<template>
  <main>
  <h1 class="text-center text-violet-500">Zrekae</h1>
  <br>
  <div class="container mx-auto bg-violet-600 bg-auto shadow-gray-400 rounded">
    <NuxtLink class="content-center px-6 py-2 bg-gray-500 font-medium text-sm hover:bg-gray-600 text-gray-100 rounded" to="/" rel="home">Home page</NuxtLink>
    <NuxtLink class="content-center px-6 py-2 bg-gray-500 font-medium text-sm hover:bg-gray-600 text-gray-100 rounded" to="/about">About</NuxtLink>

  </div>
  <br>
    <p class="text-center">Hello, World!</p>
  </main>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
