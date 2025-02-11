<template>
  <footer
    class="p-4 text-center"
    :style="footerStyle"
  >
    <p>All content is shared under CC 0, allowing it to be freely used and distributed globally.</p>
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
  backgroundColor: `var(--color-header-footer-bg, #013d7a)`, // Fallback: Deep Blue
  color: `var(--color-header-footer-text, #ebe8cf)`,         // Fallback: Cream Text
  borderTop: `1px solid var(--color-base-border, #b2ae9d)`
}))
</script>
