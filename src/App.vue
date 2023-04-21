<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    <div class="m-2 mx-4">
      <nav class="flex items-end gap-4 ">
        <span class="text-3xl">Lab of Graphic Designs</span>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <!-- <RouterView /> -->
</template>