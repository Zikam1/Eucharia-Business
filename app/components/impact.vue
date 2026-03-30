<template>
  <section ref="sectionRef" class="py-24">
    <div class="max-w-6xl mx-auto px-6">

      <!-- Heading -->
      <div class="text-center mb-16">
        <h2 class="text-4xl font-bold mb-4">Impact & Achievements</h2>
        <p class="text-xl text-gray-600">
          Measurable contributions to environmental science and policy
        </p>
      </div>

      <!-- Cards -->
      <div class="grid md:grid-cols-3 gap-8">

        <!-- YEARS -->
        <div class="text-center bg-gradient-to-br from-blue-50 to-blue-100 p-8 rounded-2xl">
          <div class="text-6xl font-bold text-blue-600 mb-2">
            {{ years }}+
          </div>
          <p class="text-gray-700 font-medium">Years of Experience</p>
          <p class="text-gray-600 text-sm mt-1">Academic & field expertise</p>
        </div>

        <!-- PUBLICATIONS -->
        <div class="text-center bg-gradient-to-br from-green-50 to-green-100 p-8 rounded-2xl">
          <div class="text-6xl font-bold text-green-600 mb-2">
            {{ publications }}+
          </div>
          <p class="text-gray-700 font-medium">Publications & Reports</p>
          <p class="text-gray-600 text-sm mt-1">Peer-reviewed research</p>
        </div>

        <!-- GLOBAL -->
        <div class="text-center bg-gradient-to-br from-purple-50 to-purple-100 p-8 rounded-2xl">
          <div class="text-6xl font-bold text-purple-600 mb-2">
            {{ reach }}
          </div>
          <p class="text-gray-700 font-medium">Reach & Collaborations</p>
          <p class="text-gray-600 text-sm mt-1">International partnerships</p>
        </div>

      </div>
    </div>
  </section>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const years = ref(0)
const publications = ref(0)
const reach = ref('')

const sectionRef = ref(null)
let observer = null
let hasAnimated = false

// Count animation
function animateValue(refVar, end, duration) {
  let start = 0
  const increment = end / (duration / 16)

  const timer = setInterval(() => {
    start += increment
    if (start >= end) {
      refVar.value = end
      clearInterval(timer)
    } else {
      refVar.value = Math.floor(start)
    }
  }, 16)
}

onMounted(() => {
  observer = new IntersectionObserver(
    ([entry]) => {
      if (entry.isIntersecting && !hasAnimated) {
        hasAnimated = true

        animateValue(years, 16, 1500)
        animateValue(publications, 150, 2000)

        setTimeout(() => {
          reach.value = 'Global'
        }, 1000)

        observer.disconnect()
      }
    },
    {
      threshold: 0.3
    }
  )

  if (sectionRef.value) {
    observer.observe(sectionRef.value)
  }
})

onUnmounted(() => {
  if (observer) observer.disconnect()
})
</script>