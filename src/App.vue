

<template>
<div>
<GridExample/>
<GridExampleTemplateAreas/>
</div>


</template>


<script setup lang="ts">
import GridExampleTemplateAreas from './components/GridExampleTemplateAreas.vue'
import GridExample from './components/GridExample.vue'
</script>

<style>
:root {
  --clr-primary-400: 263 55% 52%;
  --clr-secondary-400: 217 19% 35%;
  --clr-secondary-500: 219 29% 14%;
  --clr-neutral-100: 0 0% 100%;
  --clr-neutral-200: 210 46% 95%;
  --clr-neutral-300: 0 0% 81%;

  --ff-primary: "Barlow Semi Condensed", sans-serif;

  --fw-400: 500;
  --fw-700: 600;

  --fs-300: 0.6875rem;
  --fs-400: 0.8125rem;
  --fs-500: 1.25rem;
}
</style>
