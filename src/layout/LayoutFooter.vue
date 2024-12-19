<template>
  <footer class="p-4 text-center" :style="footerStyle">
    <p>© 2024 UNH Entomology Lab. All rights reserved.</p>
  </footer>
</template>

<script setup>
import { computed, defineProps } from 'vue'

// Accept Theme as a Prop
defineProps({
  theme: {
    type: String,
    required: true
  }
})

// Dynamically Adjust Footer Style
const footerStyle = computed(() => ({
  backgroundColor: `var(--color-base-background)`,
  color: `var(--color-base-content)`,
  borderTop: `1px solid var(--color-base-border)`
}))
</script>
