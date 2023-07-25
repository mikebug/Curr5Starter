<template>
  <button
  >
    <slot></slot>
  </button>
</template>

<script setup lang="ts">

const props = defineProps<{
  primary: boolean;
  secondary: boolean;
  text: boolean;
}>();

</script>

<style scoped></style>
