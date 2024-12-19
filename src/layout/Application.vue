<template>
  <div
    class="min-h-screen h-screen flex flex-col justify-between"
    :class="{ dark: theme === 'dark' }"
  >
    <header
      class="p-4 text-center"
      :style="{
        backgroundColor: 'var(--color-header-footer-bg)',
        color: 'var(--color-header-footer-text)'
      }"
    >
      <h1>University of New Hampshire</h1>
    </header>

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
  document.documentElement.classList.toggle('dark', theme.value === 'dark')
}
</script>
