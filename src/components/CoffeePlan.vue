<script setup>
import { ref } from "vue";
defineProps(["name"]);
const selected = ref(false);
</script>

<template>
  <div class="plan active-plan">
    <div class="description">
      <span class="title"> {{ name }}</span>
    </div>
  </div>
</template>

<style></style>
