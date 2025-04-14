<template>
  <div class="max-w-3xl mx-auto">
    <div class="bg-white rounded-lg shadow-md p-8">
      <h1 class="text-3xl font-bold text-gray-800 mb-6">About This Application</h1>
      <p class="text-gray-600 mb-4 text-justify">
        This is a simple biodata application built with Vue 3, Vite, and Tailwind CSS. It demonstrates how to create a
        modern, responsive web application with Vue's composition API and Tailwind's utility-first CSS framework.
      </p>
      <p class="text-gray-600 mb-4 text-justify">
        The application includes routing between different pages and a dedicated biodata page that showcases personal
        information in a clean, professional layout.
      </p>
      <p class="text-gray-600 text-justify">
        Feel free to explore the codebase and use it as a starting point for your own projects!
      </p>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
