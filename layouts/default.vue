<script setup lang="ts">
import Navbar from "~/components/layout/Navbar.vue";
</script>

<template>
  <div
    class="dark bg-background text-foreground flex flex-col min-h-dvh font-inter"
  >
    <Navbar />
    <div
      class="relative w-full mx-auto max-w-screen-lg px-6 lg:px-8 flex flex-col grow py-8 gap-8 md:gap-10 md:py-10 lg:gap-12 lg:py-12"
    >
      <slot />
    </div>
  </div>
</template>
