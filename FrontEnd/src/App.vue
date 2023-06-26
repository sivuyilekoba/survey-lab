<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
</script>

<template>
  <router-view :key="$route.path"></router-view>
</template>

<style>

html.dark {
  color-scheme: dark;
}

body {
  @apply bg-slate-50 text-slate-800 dark:bg-slate-800;
}

</style>
