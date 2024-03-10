<script setup lang="ts">
defineProps({
  to: {
    type: String,
    required: true,
  },
  label: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <NuxtLink
    :to="to"
    class="px-3 py-1 rounded hover:bg-primary-100 transition-colors"
    >{{ label }}</NuxtLink
  >
</template>

<style scoped>
.router-link-active,
.router-link-exact-active {
  @apply bg-primary-100;
}
</style>
