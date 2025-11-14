<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <div class="min-h-screen bg-material-grey-50">
    <!-- Header -->
    <header class="bg-material-blue-500 text-white shadow-lg">
      <div class="max-w-7xl mx-auto px-4 py-6">
        <h1 class="text-3xl font-bold">Vue 3 + TypeScript + Tailwind</h1>
        <p class="text-material-blue-100 mt-2">A basic single-page application with Material Design colors</p>
      </div>
    </header>

    <!-- Main Content -->
    <main class="max-w-7xl mx-auto px-4 py-8">
      <!-- Counter Card -->
      <div class="bg-white rounded-lg shadow-md p-6 mb-6">
        <h2 class="text-2xl font-semibold text-material-grey-800 mb-4">Interactive Counter</h2>
        <div class="flex items-center justify-center gap-4">
          <button 
            @click="count--" 
            class="bg-material-red-500 hover:bg-material-red-600 text-white font-bold py-2 px-4 rounded transition-colors"
          >
            -
          </button>
          <span class="text-4xl font-bold text-material-indigo-600">{{ count }}</span>
          <button 
            @click="count++" 
            class="bg-material-green-500 hover:bg-material-green-600 text-white font-bold py-2 px-4 rounded transition-colors"
          >
            +
          </button>
        </div>
      </div>

      <!-- Material Color Palette -->
      <div class="bg-white rounded-lg shadow-md p-6">
        <h2 class="text-2xl font-semibold text-material-grey-800 mb-4">Material Design Color Palette</h2>
        <p class="text-material-grey-600 mb-6">Showcasing various Material Design colors available in this project</p>
        
        <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-4">
          <div class="text-center">
            <div class="bg-material-red-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Red</p>
          </div>
          <div class="text-center">
            <div class="bg-material-pink-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Pink</p>
          </div>
          <div class="text-center">
            <div class="bg-material-purple-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Purple</p>
          </div>
          <div class="text-center">
            <div class="bg-material-indigo-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Indigo</p>
          </div>
          <div class="text-center">
            <div class="bg-material-blue-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Blue</p>
          </div>
          <div class="text-center">
            <div class="bg-material-cyan-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Cyan</p>
          </div>
          <div class="text-center">
            <div class="bg-material-teal-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Teal</p>
          </div>
          <div class="text-center">
            <div class="bg-material-green-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Green</p>
          </div>
          <div class="text-center">
            <div class="bg-material-lime-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Lime</p>
          </div>
          <div class="text-center">
            <div class="bg-material-yellow-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Yellow</p>
          </div>
          <div class="text-center">
            <div class="bg-material-amber-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Amber</p>
          </div>
          <div class="text-center">
            <div class="bg-material-orange-500 h-20 rounded-lg shadow-md mb-2"></div>
            <p class="text-sm text-material-grey-700">Orange</p>
          </div>
        </div>
      </div>
    </main>

    <!-- Footer -->
    <footer class="bg-material-grey-800 text-white mt-12">
      <div class="max-w-7xl mx-auto px-4 py-6 text-center">
        <p class="text-material-grey-300">Built with Vue 3, TypeScript, and Tailwind CSS</p>
      </div>
    </footer>
  </div>
</template>
