<script setup lang="ts">
import { RouterView } from 'vue-router'
import MenuBar from './components/SiteHeader.vue'
import SiteFooter from './components/SiteFooter.vue'
</script>

<template>
  <div class="flex flex-col h-full items-center justify-center text-center">
    <MenuBar />
    <main class="flex-1 container mx-auto min-h-[750px]">
      <RouterView />
    </main>
    <SiteFooter class="flex mt-auto"/>
  </div>
</template>

