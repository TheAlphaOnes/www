<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { Analytics } from '@vercel/analytics/vue';
</script>

<template>
  <Analytics />

  <RouterView />
</template>

<style scoped>

</style>
