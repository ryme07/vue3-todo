<template>
  <div>
    About view
    <p>{{ msg }}</p>
  </div>
</template>

<script setup>
import { defineProps } from "vue";
// const props = defineProps({
//   msg: { type: String, required: true },
// });

defineProps({
  msg: { type: String, required: true },
});
</script>

<style lang="scss" scoped>
</style>