<template>
  <div>{{ id }}</div>
</template>
<script lang="ts" setup>
const props = withDefaults(
  defineProps<{
    id: string | null;
  }>(),
  { id: null }
);
</script>
