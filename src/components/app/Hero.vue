<template>
  <div class="flex h-screen items-center justify-center">
    <div class="p-10  relative group">
      <Logo class="z-10" />
      <div class="">
        <div class="rounded-full bg-purple-300 h-20 opacity-60 transition-all top-0 -left-4 w-20 z-8 duration-300 blob absolute  mix-blend-multiply filter blur-xl dark:bg-blue-500 dark:mix-blend-lighten dark:blur-2xl group-hover:opacity-80" />
        <div class="rounded-full bg-yellow-300 h-20 opacity-60 transition-all top-0 -right-4 w-20 z-8 duration-300 absolute mix-blend-multiply filter blur-xl blob-1 dark:bg-purple-500 dark:mix-blend-lighten dark:blur-2xl group-hover:opacity-80" />
        <div class="rounded-full bg-pink-300 h-20 opacity-60 transition-all -bottom-5 left-0 w-20 z-8 duration-300 absolute mix-blend-multiply filter blur-xl blob-2 dark:bg-pink-500 dark:mix-blend-lighten dark:blur-2xl group-hover:opacity-80" />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

.blob {
  animation: blob 10s ease-in-out infinite
}
.blob-1 {
  animation: blob 10s ease-in-out infinite;
  animation-delay: 1s;
}
.blob-2 {
  animation: blob 10s ease-in-out infinite;
  animation-delay: 2s;
}
@keyframes blob{
 0% {
    transform: translate(0, 0), scale(1);
  }

  25% {
    transform: translate(20px, -40px) scale(1.1);
  }

  50% {
    transform: translate(0, 20px) scale(1);
  }

  75% {
    transform: translate(-20px, -15px) scale(0.8);
  }

  100% {
    transform: translate(0, 0) scale(1);
  }
}

</style>
