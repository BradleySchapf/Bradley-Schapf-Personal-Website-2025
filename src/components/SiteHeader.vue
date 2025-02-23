<template>
    <header class="w-full mb-4 bg-gray-100 ">
      <nav class="container mx-auto p-4 flex justify-center items-center gap-x-12 hover:bg-gray-200">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/blog">Blog</RouterLink>
        <RouterLink to="/portfolio">Portfolio</RouterLink>
    </nav>
  </header>
</template>

<style scoped>
.menu-bar:hover {
  background-color: #f0f0f0;
}
</style>
