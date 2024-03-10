<script setup lang="ts"></script>

<template>
  <nav class="flex gap-x-4 p-4 bg-white border-b border-b-gray-200">
    <NavItem to="/" label="Home" />
    <NavItem to="/articles" label="Articles" />
  </nav>
</template>

<style scoped>
.router-link-active,
.router-link-exact-active {
  @apply bg-primary-100 rounded;
}
</style>
