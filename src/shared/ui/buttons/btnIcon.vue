<template>
  <q-btn :icon="icon" class="btnIcon" unelevated />
</template>

<script setup lang="ts">
defineProps({
  icon: { type: String, required: true },
});
</script>

<style scoped lang="scss">
.btnIcon {
  border: 1px solid $razdelitel-razdelitel-1;
  border-radius: 12px;
  background-color: #fff;
  color: $tekst-seryy-1;
  padding: 16px;
  transition: 0.3s;
  &:hover {
    background-color: #ff663326;
    border-color: #fff;
    color: $akcentnyy-akcentnyy-2;
  }
}
</style>
