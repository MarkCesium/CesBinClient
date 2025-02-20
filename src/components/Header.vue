<script setup>
defineProps({ text: String })
</script>

<template>
  <h1 class="lg:text-5xl md:text-4xl text-3xl text-fuchsia-500 py-5 mb-5 text-center font-mono">
    {{ text }}
  </h1>
</template>
