<script setup lang="ts">
import { cn } from "@/lib/utils";
</script>

<template>
  <aside class="w-64 min-h-screen bg-gray-50 dark:bg-gray-800 border-r p-4">
    <nav class="space-y-2">
      <NuxtLink
        to="/"
        class="block px-3 py-2 rounded hover:bg-gray-200 dark:hover:bg-gray-700"
        >Home</NuxtLink
      >
      <NuxtLink
        to="/recipes"
        class="block px-3 py-2 rounded hover:bg-gray-200 dark:hover:bg-gray-700"
        >Recipes</NuxtLink
      >
      <NuxtLink
        to="/create"
        class="block px-3 py-2 rounded hover:bg-gray-200 dark:hover:bg-gray-700"
        >Add Recipe</NuxtLink
      >
    </nav>
  </aside>
</template>
