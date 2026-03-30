<template>
  <div class="min-h-screen bg-slate-50 text-slate-900">
    <!-- Hero -->
    <section class="bg-white border-b border-slate-200">
      <div class="max-w-6xl mx-auto px-6 py-16 md:py-20">
        <div class="grid lg:grid-cols-2 gap-10 items-center">
          <div>
            <p class="text-sm uppercase tracking-[0.25em] text-emerald-700 font-medium">Training & Capacity Building</p>
            <h1 class="mt-4 text-4xl md:text-6xl font-bold leading-tight max-w-2xl">
              Structured learning for environmental excellence.
            </h1>
            <p class="mt-5 text-lg text-slate-600 max-w-2xl leading-relaxed">
              Well-organized training programs for universities, institutions, NGOs, and professionals who want practical skills in environmental science, research, and policy.
            </p>

            <div class="mt-8 flex flex-wrap gap-4">
              <NuxtLink class="rounded-full bg-emerald-700 px-6 py-3 text-white font-medium hover:bg-emerald-800 transition-colors">
                Book a Session
              </NuxtLink>
              <NuxtLink class="rounded-full border border-slate-300 px-6 py-3 text-slate-800 font-medium hover:bg-slate-100 transition-colors">
                View Training Areas
              </NuxtLink>
            </div>
          </div>

          <div class="grid sm:grid-cols-2 gap-4">
            <div class="rounded-2xl bg-emerald-50 p-5 border border-emerald-100">
              <p class="text-sm text-emerald-700 font-semibold">30+</p>
              <h3 class="mt-2 text-xl font-semibold">Workshops</h3>
              <p class="mt-2 text-slate-600 text-sm">Delivered for academic and professional audiences.</p>
            </div>
            <div class="rounded-2xl bg-cyan-50 p-5 border border-cyan-100">
              <p class="text-sm text-cyan-700 font-semibold">500+</p>
              <h3 class="mt-2 text-xl font-semibold">Participants</h3>
              <p class="mt-2 text-slate-600 text-sm">Equipped with practical and research-based knowledge.</p>
            </div>
            <div class="rounded-2xl bg-amber-50 p-5 border border-amber-100 sm:col-span-2">
              <p class="text-sm text-amber-700 font-semibold">Flexible delivery</p>
              <h3 class="mt-2 text-xl font-semibold">On-site, virtual, and custom formats</h3>
              <p class="mt-2 text-slate-600 text-sm">Each program is tailored to the audience, schedule, and learning goal.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Training tracks -->
    <section class="py-16 md:py-20">
      <div class="max-w-6xl mx-auto px-6">
        <div class="text-center max-w-3xl mx-auto mb-12">
          <p class="text-sm uppercase tracking-[0.25em] text-slate-500">Training Tracks</p>
          <h2 class="mt-3 text-3xl md:text-4xl font-bold">Clear and focused learning areas</h2>
          <p class="mt-4 text-slate-600">Each module is arranged to move from understanding to real-world application.</p>
        </div>

        <div class="grid md:grid-cols-2 gap-6">
          <div class="h-full rounded-2xl bg-white p-6 border border-slate-200 shadow-sm">
            <h3 class="text-xl font-semibold">Environmental Monitoring</h3>
            <p class="mt-3 text-slate-600 leading-relaxed">Field sampling, laboratory interpretation, pollution indicators, and environmental reporting.</p>
          </div>

          <div class="h-full rounded-2xl bg-white p-6 border border-slate-200 shadow-sm">
            <h3 class="text-xl font-semibold">Research Methods & Writing</h3>
            <p class="mt-3 text-slate-600 leading-relaxed">Project design, scientific writing, proposal development, and publication support.</p>
          </div>

          <div class="h-full rounded-2xl bg-white p-6 border border-slate-200 shadow-sm">
            <h3 class="text-xl font-semibold">Policy & Sustainability</h3>
            <p class="mt-3 text-slate-600 leading-relaxed">How to translate environmental evidence into policy actions and sustainability strategies.</p>
          </div>

          <div class="h-full rounded-2xl bg-white p-6 border border-slate-200 shadow-sm">
            <h3 class="text-xl font-semibold">Leadership & Team Development</h3>
            <p class="mt-3 text-slate-600 leading-relaxed">Mentorship, institutional strengthening, and practical capacity building for long-term growth.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Audience + formats -->
    <section class="py-16 md:py-20 bg-white border-y border-slate-200">
      <div class="max-w-6xl mx-auto px-6 grid lg:grid-cols-2 gap-8">
        <div class="rounded-2xl border border-slate-200 p-6 bg-slate-50">
          <p class="text-sm uppercase tracking-[0.25em] text-slate-500">Who it is for</p>
          <div class="mt-5 space-y-4">
            <div>
              <h3 class="font-semibold text-lg">Students & Researchers</h3>
              <p class="text-slate-600">Develop stronger academic, field, and analytical skills.</p>
            </div>
            <div>
              <h3 class="font-semibold text-lg">Institutions & NGOs</h3>
              <p class="text-slate-600">Build stronger environmental practice and implementation capacity.</p>
            </div>
            <div>
              <h3 class="font-semibold text-lg">Professional Teams</h3>
              <p class="text-slate-600">Improve staff knowledge for sustainability, monitoring, and policy work.</p>
            </div>
          </div>
        </div>

        <div class="rounded-2xl border border-slate-200 p-6 bg-slate-50">
          <p class="text-sm uppercase tracking-[0.25em] text-slate-500">Delivery format</p>
          <div class="mt-5 grid sm:grid-cols-2 gap-4">
            <div class="rounded-xl bg-white p-4 border border-slate-200">
              <h3 class="font-semibold">Workshops</h3>
              <p class="mt-2 text-sm text-slate-600">Focused sessions for quick practical learning.</p>
            </div>
            <div class="rounded-xl bg-white p-4 border border-slate-200">
              <h3 class="font-semibold">Masterclasses</h3>
              <p class="mt-2 text-sm text-slate-600">Deeper learning for specialized topics and teams.</p>
            </div>
            <div class="rounded-xl bg-white p-4 border border-slate-200">
              <h3 class="font-semibold">Field Training</h3>
              <p class="mt-2 text-sm text-slate-600">Hands-on experience in monitoring and application.</p>
            </div>
            <div class="rounded-xl bg-white p-4 border border-slate-200">
              <h3 class="font-semibold">Mentoring</h3>
              <p class="mt-2 text-sm text-slate-600">Guided professional and academic development support.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Process -->
    <section class="py-16 md:py-20">
      <div class="max-w-6xl mx-auto px-6">
        <div class="text-center mb-12">
          <p class="text-sm uppercase tracking-[0.25em] text-slate-500">Process</p>
          <h2 class="mt-3 text-3xl md:text-4xl font-bold">A better arranged delivery flow</h2>
        </div>

        <div class="grid md:grid-cols-3 gap-6">
          <div class="rounded-2xl bg-white p-6 border border-slate-200 shadow-sm text-center">
            <div class="w-12 h-12 mx-auto rounded-full bg-emerald-100 text-emerald-700 flex items-center justify-center font-bold">1</div>
            <h3 class="mt-4 text-xl font-semibold">Assessment</h3>
            <p class="mt-2 text-slate-600">We identify the audience, level, and expected learning goals.</p>
          </div>

          <div class="rounded-2xl bg-white p-6 border border-slate-200 shadow-sm text-center">
            <div class="w-12 h-12 mx-auto rounded-full bg-cyan-100 text-cyan-700 flex items-center justify-center font-bold">2</div>
            <h3 class="mt-4 text-xl font-semibold">Delivery</h3>
            <p class="mt-2 text-slate-600">Sessions are taught through clear structure, examples, and practical tasks.</p>
          </div>

          <div class="rounded-2xl bg-white p-6 border border-slate-200 shadow-sm text-center">
            <div class="w-12 h-12 mx-auto rounded-full bg-amber-100 text-amber-700 flex items-center justify-center font-bold">3</div>
            <h3 class="mt-4 text-xl font-semibold">Impact</h3>
            <p class="mt-2 text-slate-600">Participants leave with skills they can apply immediately in real settings.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA -->
    <section class="pb-20">
      <div class="max-w-6xl mx-auto px-6">
        <div class="rounded-[28px] bg-slate-900 text-white p-8 md:p-10 text-center">
          <h2 class="text-3xl md:text-4xl font-bold">Need a more customized training program?</h2>
          <p class="mt-4 text-slate-300 max-w-2xl mx-auto">
            Sessions can be arranged for your institution, team, or event with content tailored to your exact goals.
          </p>
          <div class="mt-7 flex flex-wrap justify-center gap-4">
            <NuxtLink class="rounded-full bg-emerald-600 px-6 py-3 text-white font-medium hover:bg-emerald-700 transition-colors">
              Request Proposal
            </NuxtLink>
            <NuxtLink class="rounded-full border border-slate-500 px-6 py-3 text-white font-medium hover:bg-slate-800 transition-colors">
              Contact Now
            </NuxtLink>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
