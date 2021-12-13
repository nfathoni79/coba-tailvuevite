<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1 class="text-3xl font-bold text-gray-900">{{ msg }}</h1>

  <p class="text-gray-900">
    Recommended IDE setup:
    <a
      class="text-green-600 hover:text-green-500"
      href="https://code.visualstudio.com/"
      target="_blank">VSCode</a>
    +
    <a
      class="text-green-600 hover:text-green-500"
      href="https://github.com/johnsoncodehk/volar"
      target="_blank">Volar</a>
  </p>

  <p class="text-gray-900">
    <a
      class="text-green-600 hover:text-green-500"
      href="https://vitejs.dev/guide/features.html"
      target="_blank">Vite Documentation</a>
    |
    <a
      class="text-green-600 hover:text-green-500"
      href="https://v3.vuejs.org/"
      target="_blank">Vue 3 Documentation</a>
  </p>

  <button
    class="mt-4 px-4 py-2 bg-green-600 text-white font-semibold rounded-md hover:bg-green-500 focus:ring-2 ring-offset-2 ring-green-600 active:bg-green-700"
    type="button"
    @click="count++"
  >
    count is: {{ count }}
  </button>

  <p class="mt-4 text-gray-900">
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>
