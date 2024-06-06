<template>
  <Btn class="btn--green"><slot></slot></Btn>
</template>

<script setup lang="ts">
import Btn from './btn.vue';
</script>

<style scoped lang="scss">
.btn--green {
  background-color: $akcentnyy-akcentnyy-1;
}
</style>
