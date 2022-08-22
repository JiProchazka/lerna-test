<script setup lang="ts">
defineProps({
  badge: {
    type: String,
  },
  label: {
    type: String,
  },
});
</script>

<template>
  <div>
    <q-badge color="orange" text-color="black" :label="badge" />
    <q-btn color="primary" :label="label" />
  </div>
</template>

<style lang="scss" scoped></style>
