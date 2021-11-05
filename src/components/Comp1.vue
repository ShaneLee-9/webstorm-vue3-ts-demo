<script setup lang="ts">
defineProps<{
  btnColor: string
}>()
</script>

<template>
  <div>
    Comp1 prop: {{ btnColor }}
  </div>
</template>
