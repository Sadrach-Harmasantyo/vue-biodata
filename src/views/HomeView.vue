<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <div class="bg-white rounded-lg shadow-md p-6">
    <h1 class="text-3xl font-bold text-gray-800 mb-6 text-center">Welcome to Vue Biodata</h1>
    <p class="text-gray-600 mb-8 text-center max-w-2xl mx-auto">
      This application demonstrates a simple biodata/CV page built with Vue 3 and Tailwind CSS.
      Click on "My Biodata" in the navigation to view the CV page.
    </p>
    <div class="border-t border-gray-200 pt-6">
      <TheWelcome />
    </div>
  </div>
</template>
