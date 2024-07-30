<script setup>
import { ref } from "vue";
defineProps(["name"]);
const selected = ref(false);
</script>

<template>
  <div
    @click="selected = !selected"
    class="plan"
    :class="{ 'active-plan': selected }"
  >
    <div class="description">
      <span class="title"> {{ name }}</span>
    </div>
  </div>
</template>

<style></style>
