<script setup>
import { ref } from "vue";
defineProps(["name"]);

const selected = ref(false);
function selectPlan() {
  selected.value = !selected.value;
}
</script>

<template>
  <div @click="selectPlan" class="plan" :class="{ 'active-plan': selected }">
    <div class="description">
      <span class="title"> {{ name }}</span>
    </div>
  </div>
</template>

<style></style>
