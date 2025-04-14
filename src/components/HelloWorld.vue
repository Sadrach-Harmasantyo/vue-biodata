<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="text-center md:text-left">
    <h1 class="text-3xl font-bold text-vue-green">{{ msg }}</h1>
    <h3 class="text-base text-gray-600 mt-2">
      Built with
      <a href="https://vite.dev/" target="_blank" rel="noopener" class="font-medium">Vite</a> +
      <a href="https://vuejs.org/" target="_blank" rel="noopener" class="font-medium">Vue 3</a>
    </h3>
  </div>
</template>
