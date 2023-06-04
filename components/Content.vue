<script setup>
import { VueTyper } from "vue-typer";
</script>

<template>
  <div class="text-white">
    <!-- <h1 class="font-bold text-center font-mono text-5xl"> -->
    <div class="w-full">
      <vue-typer
        text="NICE TO MEET YOU I'M HIBIKI"
        class="flex justify-center text-5xl font-mono typed typed typed"
        repeat="3"
        caret-animation="smooth"
      ></vue-typer>
    </div>
    <!-- </h1> -->
  </div>
</template>

<style>
.typed {
  color: white !important;
}
</style>
