<script setup>
import "bootstrap"
import 'bootstrap/dist/css/bootstrap.min.css'
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

    <div class="">
      <nav class="">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>

  </header>

  <RouterView />
</template>

<style scoped>

</style>
