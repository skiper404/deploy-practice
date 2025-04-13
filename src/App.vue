<script setup>
import { CheckCircleIcon } from '@heroicons/vue/24/outline';
</script>

<template>
  <div class="bg-gray-900 h-screen">
    <div class="flex justify-center">
      <h1
        class="text-center text-5xl bg-gradient-to-r from-orange-500 to-green-500 text-transparent bg-clip-text p-2"
      >
        Deploy practice
      </h1>
    </div>
    <ul
      class="grid sm:grid-cols-2 grid-cols-1 gap-5 p-3 mt-5 mx-auto max-w-[900px]"
    >
      <li>
        <div
          class="bg-gradient-to-br from-red-500 to-orange-500 rounded-xl p-0.5 hover:from-red-700 hover:to-orange-700"
        >
          <div class="bg-gray-900 rounded-xl">
            <div
              class="text-3xl text-center bg-gradient-to-tl bg-clip-text from-red-600 to-yellow-500 text-transparent rounded-xl p-1 flex items-center justify-center"
            >
              Firebace
            </div>
          </div>
        </div>
      </li>
      <li>
        <div
          class="bg-gradient-to-br from-teal-300 to-lime-500 rounded-xl p-0.5 hover:from-teal-500 hover:to-lime-700"
        >
          <div class="rounded-xl bg-gray-900">
            <div
              class="text-3xl text-center bg-gradient-to-tl from-teal-300 to-lime-600 bg-clip-text text-transparent rounded-xl bg-gray-900 p-1"
            >
              Netlify
            </div>
          </div>
        </div>
      </li>
      <li>
        <div
          class="bg-gradient-to-br from-blue-600 to-violet-600 p-0.5 rounded-xl hover:from-blue-800 hover:to-violet-800"
        >
          <div class="bg-gray-900 rounded-xl">
            <div
              class="text-3xl text-center text-transparent bg-gradient-to-tl from-blue-700 to-violet-600 bg-clip-text p-1"
            >
              Vercel
            </div>
          </div>
        </div>
      </li>
      <li>
        <div
          class="bg-gradient-to-tr from-stone-400 to-stone-600 rounded-xl p-0.5 hover:from-stone-600 hover:to-stone-800"
        >
          <div class="rounded-xl bg-gray-900">
            <div
              class="flex items-center justify-center gap-1 text-3xl text-transparent bg-gradient-to-bl from-zinc-300 to-zinc-600 bg-clip-text p-1"
            >
              <span>GitHub</span>
              <CheckCircleIcon class="size-10 text-lime-500" />
            </div>
          </div>
        </div>
      </li>
    </ul>
  </div>
</template>

<style scoped></style>
