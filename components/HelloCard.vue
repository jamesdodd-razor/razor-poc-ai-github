<template>
  <div class="text-center p-8 bg-white rounded-lg shadow-xl transform hover:scale-105 transition-transform duration-300">
    <h1 class="text-4xl font-bold text-indigo-600 mb-4">{{ title }}</h1>
    <p class="text-gray-600">{{ description }}</p>
  </div>
</template>

<script setup>
defineProps({
  title: {
    type: String,
    default: 'Hello, World!'
  },
  description: {
    type: String,
    default: 'Welcome to our Nuxt-powered page'
  }
})
</script> 