<template>
  <q-btn no-caps class="btn"><slot>default text</slot></q-btn>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.btn {
  color: #fff;
  border-radius: 12px;
  font-family: $Inter-500;
  font-size: 16px;
  line-height: 24px;
  padding-top: 16px;
  padding-bottom: 16px;
  width: 100%;
}
</style>
