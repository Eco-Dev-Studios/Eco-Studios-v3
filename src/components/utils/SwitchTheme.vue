<script setup lang="ts">
import { toggleDark } from '../../composables'
</script>

<template>
  <button class="p-2 !outline-none" @click="toggleDark()">
    <div class="fill-current text-gray-400" i="carbon-sun dark:carbon-moon" />
  </button>
</template>
