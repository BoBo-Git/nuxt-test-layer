<script setup lang="ts">
const props = defineProps<{
  title: string
}>()
</script>

<template>
  <div>
    Box component from base layer {{ props.title }}
  </div>
</template>

<style scoped>

</style>