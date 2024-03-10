<script setup lang="ts"></script>

<template>
  <div class="flex flex-col min-h-dvh">
    <header class="sticky top-0 z-index-nav">
      <AppNav />
    </header>
    <main class="flex-grow p-4">
      <slot />
    </main>
    <AppFooter />
  </div>
</template>
