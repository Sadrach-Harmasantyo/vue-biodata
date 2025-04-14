<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="min-h-screen bg-gray-50">
    <header class="py-6 mb-8 bg-white shadow-sm">
      <div class="container mx-auto px-4 flex flex-col md:flex-row items-center justify-between">
        <div class="flex items-center mb-4 md:mb-0">
          <img alt="Vue logo" class="h-16 w-16 mr-4" src="@/assets/logo.svg" />
          <HelloWorld msg="Vue Biodata App" />
        </div>

        <nav class="flex space-x-1 text-sm md:text-base">
          <RouterLink to="/" class="px-4 py-2 rounded-md hover:bg-gray-100">Home</RouterLink>
          <RouterLink to="/about" class="px-4 py-2 rounded-md hover:bg-gray-100">About</RouterLink>
          <RouterLink to="/biodata" class="px-4 py-2 rounded-md bg-vue-green text-white hover:bg-opacity-90">
            My Biodata
          </RouterLink>
        </nav>
      </div>
    </header>

    <main class="container mx-auto px-4 pb-12">
      <RouterView />
    </main>

    <footer class="bg-vue-dark text-white py-8 mt-12">
      <div class="container mx-auto px-4 text-center">
        <p>© {{ new Date().getFullYear() }} Vue Biodata App. All rights reserved.</p>
        <div class="mt-4 flex justify-center space-x-4">
          <a href="#" class="text-gray-300 hover:text-white hover:bg-transparent">Privacy Policy</a>
          <a href="#" class="text-gray-300 hover:text-white hover:bg-transparent">Terms of Service</a>
          <a href="#" class="text-gray-300 hover:text-white hover:bg-transparent">Contact</a>
        </div>
      </div>
    </footer>
  </div>
</template>
