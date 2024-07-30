<script setup>
import { ref } from "vue";
import CoffeePlan from "./CoffeePlan.vue";

const plans = ref(["The Single", "The Curious", "The Addict", "The Hacker"]);
function handleSelectedCoffeePlan(name) {}
</script>

<template>
  <div class="plans">
    <CoffeePlan
      v-for="plan in plans"
      :key="plan"
      :name="plan"
      @selected="handleSelectedCoffeePlan($event)"
    ></CoffeePlan>
  </div>
</template>

<style scoped></style>
