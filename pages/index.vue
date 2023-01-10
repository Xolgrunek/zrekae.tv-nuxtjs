<template>
  <main>
    <NuxtLink to="/">Home page</NuxtLink>
    <NuxtLink to="/about">About</NuxtLink>
  </main>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
<style>
  .red {
    color:red;
  }
</style>
