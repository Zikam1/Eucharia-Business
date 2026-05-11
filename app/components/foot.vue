<template>
  <footer class="bg-white text-slate-700 border-t border-slate-200">
    <div class="max-w-6xl mx-auto px-6 py-16">
      <div class="grid lg:grid-cols-[1.2fr_1fr_1fr] gap-10">
        <div>
          <p class="text-2xl text-bold-400">Professor Eucharia Nwaichi</p>
          <h2 class="mt-3 text-xl font-semibold text-slate-500">
            Advancing environmental science through research, policy, and training.
          </h2>
          <p class="mt-4 text-slate-600 leading-relaxed max-w-md">
            Building meaningful impact through collaboration, knowledge sharing, and sustainable environmental solutions.
          </p>

          <div class="mt-6 flex gap-3">
            <NuxtLink 
                href="https://www.linkedin.com/in/eucharia/" 
                class="px-4 py-2 rounded-full border border-slate-300 text-sm hover:bg-slate-100 transition-colors"
              >
                LinkedIn
              </NuxtLink>
            <a href="#" class="px-4 py-2 rounded-full border border-slate-300 text-sm hover:bg-slate-100 transition-colors">Email</a>
          </div>
        </div>

        <div>
          <h3 class="text-lg font-semibold text-slate-900 mb-4">Quick Links</h3>
          <ul class="space-y-3 text-slate-600">
            <li><NuxtLink to="/" class="hover:text-slate-900 transition-colors">Home</NuxtLink></li>
            <li><NuxtLink to="/about" class="hover:text-slate-900 transition-colors">About</NuxtLink></li>
        
            <li><NuxtLink to="/training" class="hover:text-slate-900 transition-colors">Training</NuxtLink></li>
            <li><NuxtLink to="/contact" class="hover:text-slate-900 transition-colors">Contact</NuxtLink></li>
          </ul>
        </div>

        <div>
          <h3 class="text-lg font-semibold text-slate-900 mb-4">Contact</h3>
          <div class="space-y-3 text-slate-600 text-sm leading-6">
            <p>Email: nodullm@yahoo.com</p>
            <p>Available for research, consulting, speaking, and capacity development.</p>
            <p class="text-emerald-400 font-medium">Availabilty 24/7</p>
          </div>
        </div>
      </div>

      <div class="mt-12 pt-6 border-t border-slate-200 flex flex-col md:flex-row justify-between gap-4 text-sm text-slate-500">
        <p>© 2026 Prof. Eucharia Oluchi Nwaichi. All rights reserved.</p>
        
      </div>
    </div>
  </footer>
</template>
