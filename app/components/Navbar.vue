<template>
  <header class="bg-white shadow-sm sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
      <NuxtLink to="/"  class="text-xl font-bold text-green-700">
        Prof. Nwaichi
      </NuxtLink>

      <!-- Desktop Menu -->
      <nav class="hidden md:flex items-center space-x-8 text-gray-700 font-medium">
        <NuxtLink to="/" class="hover:text-blue-700">Home</NuxtLink>
        <NuxtLink to="/about" class="hover:text-blue-700">About</NuxtLink>
        <NuxtLink to="/research" class="hover:text-blue-700">Research</NuxtLink>
       
        <NuxtLink to="/training" class="hover:text-blue-700">Training</NuxtLink>
        <NuxtLink to="/contact" class="hover:text-blue-700">Contact</NuxtLink>
      </nav>

      <!-- CTA Button -->
      <div class="hidden md:block">
        <NuxtLink
          to="/services"
          class="bg-green-700 text-white px-5 py-2 rounded-lg hover:bg-green-800 transition"
        >
          Book Consultation
        </NuxtLink>
      </div>

      <!-- Mobile Menu Button -->
      <button @click="toggleMenu" class="md:hidden text-gray-700">
        <svg v-if="!isOpen" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16" />
        </svg>

        <svg v-else xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </div>

    <!-- Mobile Menu -->
    <div v-if="isOpen" class="md:hidden bg-white border-t">
      <div class="flex flex-col space-y-4 px-6 py-4 text-gray-700 font-medium">
        <NuxtLink to="/" @click="closeMenu">Home</NuxtLink>
        <NuxtLink to="/about" @click="closeMenu">About</NuxtLink>
        <NuxtLink to="/research" @click="closeMenu">Research</NuxtLink>
        
        <NuxtLink to="/training" @click="closeMenu">Training</NuxtLink>
        <NuxtLink to="/contact" @click="closeMenu">Contact</NuxtLink>

        <NuxtLink
          to="/services"
          class="bg-blue-700 text-white text-center py-2 rounded-lg"
          @click="closeMenu"
        >
          Book Consultation
        </NuxtLink>
      </div>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'

const isOpen = ref(false)

const toggleMenu = () => {
  isOpen.value = !isOpen.value
}

const closeMenu = () => {
  isOpen.value = false
}
</script>