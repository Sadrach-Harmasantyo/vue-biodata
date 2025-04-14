<template>
  <div class="flex items-start mb-8 relative">
    <div class="hidden md:flex items-center justify-center w-12 h-12 rounded-lg border border-gray-200 bg-white mr-4 text-vue-green">
      <slot name="icon"></slot>
    </div>
    <div class="flex-1">
      <h3 class="text-xl font-medium text-gray-800 mb-2">
        <slot name="heading"></slot>
      </h3>
      <div class="text-gray-600 text-justify">
        <slot></slot>
      </div>
    </div>
  </div>
</template>
