<script setup lang="ts">
import { RouterView } from 'vue-router'
import MenuBar from './components/SiteHeader.vue'
</script>

<template>
  <div class="flex flex-col h-full items-center justify-center text-center">
    <MenuBar />
    <main class="flex-1 container mx-auto px-4">
      <RouterView />
    </main>
  </div>
</template>

