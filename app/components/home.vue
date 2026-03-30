<template>
  <div class="bg-gradient-to-br from-slate-50 to-white text-gray-900 min-h-screen">

    <!-- HERO SECTION -->
  <section class="relative bg-white py-32 overflow-hidden">
  <div class="max-w-6xl mx-auto px-6 lg:px-8">
    <div class="lg:grid lg:grid-cols-12 lg:gap-8 lg:items-center">
      
      <!-- Left Side: Text -->
      <div class="sm:text-center lg:col-span-7 lg:text-left">
        <div class="inline-block px-4 py-2 bg-green-100 text-green-800 rounded-full text-sm font-medium mb-6 tracking-wide shadow-sm">
          Professor • Consultant • Policy Expert
        </div>
        
        <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-gray-900 leading-tight mb-6">
          Driving Environmental Science into Global Policy & Practice
        </h1>
        
        <p class="text-lg sm:text-xl text-gray-700 mb-8 max-w-xl">
          Prof. Eucharia Oluchi Nwaichi specializes in environmental monitoring, remediation, and transforming cutting-edge research into actionable policies across international platforms.
        </p>
        
        <div class="flex flex-col sm:flex-row sm:justify-start gap-4">
          <NuxtLink
            class="bg-green-600 hover:bg-green-700 text-white px-8 py-3 rounded-full font-semibold shadow-lg transition-transform transform hover:scale-105"
          >
            Work With Me
          </NuxtLink>
          <NuxtLink
            class="border-2 border-gray-300 text-gray-700 px-8 py-3 rounded-full font-semibold hover:bg-gray-100 transition-colors"
          >
            View Publications
          </NuxtLink>
        </div>
      </div>

      <!-- Right Side: Image/Visual -->
      <div class="mt-12 lg:mt-0 lg:col-span-5 flex justify-center lg:justify-end relative">
        <div class="w-96 h-96 md:w-[420px] md:h-[420px] lg:w-[500px] lg:h-[500px] bg-gradient-to-tr from-blue-400 via-green-400 to-purple-400 rounded-3xl shadow-2xl overflow-hidden animate-pulse">
          <!-- Replace with actual image if available -->
          <img 
            src="/assets/xc1.jpg" 
            alt="Prof. Eucharia Oluchi Nwaichi" 
            class="w-full h-full object-cover rounded-3xl"
          >
        </div>
      </div>
    </div>
  </div>
</section>

    <!-- ABOUT SECTION -->
    <section class="py-24">
  <div class="max-w-6xl mx-auto px-6">
    <div class="grid lg:grid-cols-2 gap-16 items-center">

      <!-- IMAGE SIDE -->
      <div class="order-2 lg:order-1">
        <div class="w-full h-96 relative">

          <!-- Main Image -->
          <img 
            src="/assets/xc.jpg" 
            alt="Prof. Eucharia Nwaichi"
            class="w-full h-full object-cover rounded-2xl shadow-xl transition-transform duration-500 hover:scale-105"
          />

          <!-- Overlay -->
          <div class="absolute inset-0 bg-gradient-to-t from-black/20 to-transparent rounded-2xl"></div>

          <!-- Floating Badge -->
          <div class="absolute bottom-4 left-4 bg-white px-4 py-2 rounded-lg shadow-md">
            <p class="text-sm font-semibold text-gray-800">
              16+ Years Experience
            </p>
          </div>

        </div>
      </div>

      <!-- TEXT SIDE -->
      <div class="order-1 lg:order-2">
        <h2 class="text-4xl md:text-5xl font-bold leading-tight mb-6">
          Bridging Scientific Research with Real-World Environmental Solutions.
        </h2>

        <p class="text-lg text-gray-600 leading-relaxed mb-8">
          With over 16 years of academic and field experience, Prof. Nwaichi has
          contributed to shaping environmental sustainability practices through
          evidence-based research and policy engagement.
        </p>

        <!-- Trust Indicators -->
        <div class="flex items-center gap-4">

          <!-- Avatars -->
          <div class="flex -space-x-2">
            <div class="w-10 h-10 bg-blue-500 rounded-full border-2 border-white"></div>
            <div class="w-10 h-10 bg-green-500 rounded-full border-2 border-white"></div>
            <div class="w-10 h-10 bg-purple-500 rounded-full border-2 border-white"></div>
          </div>

          <span class="text-gray-600">
            Trusted by global organizations
          </span>
        </div>

      </div>

    </div>
  </div>
</section>

    <!-- EXPERTISE SECTION -->
    <section class="py-24 bg-gray-50">
      <div class="max-w-6xl mx-auto px-6">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold mb-4">Areas of Expertise</h2>
          <p class="text-xl text-gray-600 max-w-2xl mx-auto">
            Comprehensive expertise spanning environmental science, policy, and sustainable development
          </p>
        </div>
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
          <div class="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-shadow">
            <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center mb-4">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-2">Environmental Monitoring</h3>
            <p class="text-gray-600">Advanced techniques for tracking environmental health and pollution levels</p>
          </div>
          <div class="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-shadow">
            <div class="w-12 h-12 bg-green-100 rounded-xl flex items-center justify-center mb-4">
              <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-2">Remediation & Sustainability</h3>
            <p class="text-gray-600">Innovative solutions for environmental cleanup and sustainable practices</p>
          </div>
          <div class="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-shadow">
            <div class="w-12 h-12 bg-purple-100 rounded-xl flex items-center justify-center mb-4">
              <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-2">Research to Policy</h3>
            <p class="text-gray-600">Translating scientific findings into effective environmental policies</p>
          </div>
          <div class="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-shadow">
            <div class="w-12 h-12 bg-orange-100 rounded-xl flex items-center justify-center mb-4">
              <svg class="w-6 h-6 text-orange-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.746 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-2">Training & Capacity Development</h3>
            <p class="text-gray-600">Empowering professionals with cutting-edge environmental knowledge</p>
          </div>
        </div>
      </div>
    </section>

  <impact />

    <!-- THOUGHT LEADERSHIP -->
    <section class="py-24 bg-gray-50">
      <div class="max-w-6xl mx-auto px-6">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold mb-4">Thought Leadership</h2>
          <p class="text-xl text-gray-600">Driving innovation in environmental policy and gender equity in science</p>
        </div>
        <div class="grid md:grid-cols-2 gap-12">
          <div class="bg-white p-8 rounded-2xl shadow-lg">
            <div class="w-16 h-16 bg-blue-100 rounded-xl flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
              </svg>
            </div>
            <h3 class="text-2xl font-semibold mb-4">Environmental Risk and Policy Integration</h3>
            <p class="text-gray-600 leading-relaxed">
              Developing comprehensive frameworks that seamlessly align scientific data with policy decisions,
              ensuring evidence-based environmental governance at local and international levels.
            </p>
          </div>
          <div class="bg-white p-8 rounded-2xl shadow-lg">
            <div class="w-16 h-16 bg-pink-100 rounded-xl flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-pink-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
              </svg>
            </div>
            <h3 class="text-2xl font-semibold mb-4">Women in Science Advocacy</h3>
            <p class="text-gray-600 leading-relaxed">
              Leading transformative initiatives that empower women in STEM fields globally,
              fostering inclusive environments for scientific advancement and gender equity.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA SECTION -->

<section id="contact" class="py-32 bg-gray-900 text-white">
      <div class="max-w-4xl mx-auto px-6 text-center">
        <h2 class="text-4xl font-light mb-8">Let's Connect</h2>
        <p class="text-xl text-gray-300 mb-12 leading-relaxed">
          Interested in collaboration, research opportunities, or learning more about my work in environmental science and policy?
        </p>
        <div class="flex flex-col sm:flex-row gap-4 justify-center">
          <NuxtLink class="px-8 py-3 bg-white text-gray-900 rounded-full hover:bg-gray-100 transition-colors font-medium">
            Get In Touch
          </NuxtLink>
          <NuxtLink to="/" class="px-8 py-3 border border-white text-white rounded-full hover:bg-white hover:text-gray-900 transition-colors font-medium">
            View My Work
          </NuxtLink>
        </div>
      </div>
    </section>
   

  </div>
</template>
<style>

  @keyframes fade-in {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .animate-fade-in {
    animation: fade-in 1s ease-out forwards;
  }
</style>