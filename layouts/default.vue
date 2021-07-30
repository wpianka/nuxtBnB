<template>
<div class="app">
  <header class="app-header">
    <div class="app-logo">
      <img src="images/logo.svg" alt="">
    </div>
    <div class="app-search">
      tu bedzie search.
    </div>
  </header>
  <header style="background-color: #eee;">
    <nuxt-link to="/">Home</nuxt-link>
  </header>
  <nuxt />
</div>
</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>

</style>
