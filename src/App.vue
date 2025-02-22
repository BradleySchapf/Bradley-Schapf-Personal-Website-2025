<script setup lang="ts">
import { RouterView } from 'vue-router'
import MenuBar from './components/MenuBar.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <MenuBar />
    <main class="flex-1">
      <RouterView />
    </main>
  </div>
</template>

