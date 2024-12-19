<template>
  <div class="min-h-screen h-screen flex flex-col justify-between">
    <div class="flex flex-col flex-grow">
      <LayoutHeader @toggle-theme="toggleTheme" />
      <slot />
    </div>
    <LayoutFooter :theme="theme" />
  </div>
</template>

<script setup>
import { ref } from 'vue'
import LayoutHeader from '@/components/Layout/LayoutHeader.vue'
import LayoutFooter from '@/layout/LayoutFooter.vue'

// Manage Theme State
const theme = ref('light') // Default to light theme

const toggleTheme = () => {
  theme.value = theme.value === 'light' ? 'dark' : 'light'
}
</script>
