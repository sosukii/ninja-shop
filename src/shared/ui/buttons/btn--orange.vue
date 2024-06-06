<template>
  <Btn class="btn--orange"><slot></slot></Btn>
</template>

<script setup lang="ts">
import Btn from './btn.vue';
</script>

<style scoped lang="scss">
.btn--orange {
  background-color: $akcentnyy-akcentnyy-2;
}
</style>
