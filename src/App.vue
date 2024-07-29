<script setup>
import CoffeePlan from "./components/CoffeePlan.vue";
</script>

<template>
  <div class="content">
    <h1 class="title">Coffee Plans</h1>

    <h2 class="subtitle">
      We travel the world to source the very best single origin coffee for you
    </h2>

    <div class="plans">
      <div class="plan">
        <div class="description">
          <span class="title"> The Single </span>
        </div>
      </div>

      <div class="plan">
        <div class="description">
          <span class="title"> The Curious </span>
        </div>
      </div>

      <div class="plan">
        <div class="description">
          <span class="title"> The Addict </span>
        </div>
      </div>
      <CoffeePlan>The Hacker</CoffeePlan>
    </div>
  </div>
</template>

<style scoped></style>
