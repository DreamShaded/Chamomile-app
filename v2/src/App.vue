<template>
  <div class="page">
    <ChamomileInput
      name="input"
      id="input1"
      :is-disabled="false"
      type="text"
    />
    <ChamomileDatepicker
      ...
    />
  </div>
</template>

<script setup lang="ts">
import { ChamomileInput, ChamomileDatepicker }  from "Chamomile-UI";

</script>
