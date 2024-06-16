<template>
  <div class="box">
    <span class="box__label">{{ label }}</span>
    <input
      v-model="userInput"
      class="box__input"
      type="text"
      @input="(e) => $emit('userInput', userInput)"
    />
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const userInput = ref<string>('');
defineProps({
  label: { type: String, required: true },
});
</script>

<style scoped lang="scss">
.box {
  display: flex;
  flex-direction: column;
  gap: 4px;
  font-family: $Inter-400;
  font-size: 14px;
  line-height: 20px;
  &__label {
    color: $tekst-seryy-3;
  }
  &__input {
    background-color: $fon-fon-dlya-inputov;
    border-radius: 12px;
    padding: 12px 16px;
    border: none;
    outline: none;
  }
}
</style>
