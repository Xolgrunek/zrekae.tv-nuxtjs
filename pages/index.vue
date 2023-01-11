<template>
  <main>
    <BaseButton class="px-6 py-2 bg-gray-500 font-medium text-sm hover:bg-gray-600 text-gray-100 rounded" to="/" rel="next">Home page</BaseButton>
    <NuxtLink to="/about">About</NuxtLink>
  </main>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
