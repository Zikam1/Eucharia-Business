<template>
  <section class="min-h-screen bg-slate-50 py-20 md:py-24">
    <div class="max-w-6xl mx-auto px-6">
      <div class="grid lg:grid-cols-2 gap-10 items-start">

        <div>
          <p class="text-sm uppercase tracking-[0.25em] text-emerald-700 font-medium">Contact</p>
          <h1 class="mt-4 text-4xl md:text-5xl font-bold leading-tight text-slate-900">
            Let’s start a meaningful conversation.
          </h1>
          <p class="mt-5 text-lg text-slate-600 leading-relaxed max-w-xl">
            Reach out for research collaborations, consulting, speaking engagements, or training opportunities.
            I’d be glad to hear from you.
          </p>

          <div class="mt-8 space-y-4">
            <div class="rounded-2xl bg-white border border-slate-200 p-5 shadow-sm">
              <p class="text-sm text-slate-500">Email</p>
              <p class="mt-1 font-semibold text-slate-900">nodullm@yahoo.com</p>
            </div>

            <div class="rounded-2xl bg-white border border-slate-200 p-5 shadow-sm">
              <p class="text-sm text-slate-500">Available for</p>
              <p class="mt-1 font-semibold text-slate-900">Consulting, Research, Training & Public Speaking</p>
            </div>

            <div class="rounded-2xl bg-emerald-700 text-white p-5 shadow-sm">
              <p class="text-sm text-emerald-100">Response time</p>
              <p class="mt-1 font-semibold">Usually within 1–2 business days</p>
            </div>
          </div>
        </div>

        <div class="bg-white p-8 rounded-3xl shadow-lg border border-slate-200">
          <div class="mb-6">
            <h2 class="text-2xl font-bold text-slate-900">Send a Message</h2>
            <p class="text-slate-600 mt-2">Fill in your details and message below.</p>
          </div>

          <form class="space-y-5">
            <div class="grid sm:grid-cols-2 gap-4">
              <input
                class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none focus:border-emerald-600"
                placeholder="First Name"
              />
              <input
                class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none focus:border-emerald-600"
                placeholder="Last Name"
              />
            </div>

            <input
              class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none focus:border-emerald-600"
              placeholder="Email Address"
            />

            <input
              class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none focus:border-emerald-600"
              placeholder="Subject"
            />

            <textarea
              class="w-full rounded-xl border border-slate-300 px-4 py-3 outline-none focus:border-emerald-600 resize-none"
              rows="5"
              placeholder="Your Message"
            ></textarea>

            <button class="w-full bg-slate-900 text-white py-4 rounded-xl font-semibold hover:bg-slate-800 transition-colors">
              Send Message
            </button>
          </form>
        </div>

      </div>
    </div>
  </section>
</template>