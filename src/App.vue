<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Eco Development Studios - Digital Development and Design Studios',
  meta: [
    { name: 'description', content: 'Construimos y diseñamos experiencias digitales.' },
  ],
})
</script>

<template>
  <router-view />
</template>
