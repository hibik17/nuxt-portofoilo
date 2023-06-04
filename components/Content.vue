<script setup>
import { VueTyper } from "vue-typer";
</script>

<template>
  <div class="text-white">
    <!-- <h1 class="font-bold text-center font-mono text-5xl"> -->
    <div class="w-full">
      <vue-typer
        text="I'M ADENKEKAN WONDERFUL"
        class="vue-typer flex justify-center text-white text-5xl font-mono"
        repeat="3"
      ></vue-typer>
    </div>
    <!-- </h1> -->
  </div>
</template>

<style>
.vue-typer {
  color: white;
  display: flex;
  justify-content: center;
  font-size: 60px;
  font-style: monospace;
}
</style>
