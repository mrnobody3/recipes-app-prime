<script setup lang="ts">
import Header from "@/components/layout/Header.vue";
import Sidebar from "@/components/layout/Sidebar.vue";
</script>

<template>
  <div class="flex min-h-screen">
    <Sidebar />

    <div class="flex-1 flex flex-col">
      <Header />

      <main class="p-4 flex-1">
        <slot />
      </main>
    </div>
  </div>
</template>
