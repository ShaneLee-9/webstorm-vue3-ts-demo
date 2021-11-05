<script setup lang="ts">
interface Comp2Props {
  btnColor: string
}

defineProps<Comp2Props>()
</script>

<template>
  <div>
    Comp2 prop: {{ btnColor }}
  </div>
</template>
