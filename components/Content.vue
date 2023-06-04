<script setup>
import { VueTyper } from "vue-typer";
</script>

<template>
  <div class="text-white">
    <div class="w-[70%] m-auto">
      <vue-typer
        text="NICE TO MEET YOU I'M HIBIKI"
        class="flex justify-start text-5xl font-mono typed typed typed mt-10 mb-10 fadeIn_Title"
        repeat="3"
        caret-animation="smooth"
      ></vue-typer>
      <p class="text-white text-2xl font-thin mb-10 fadeIn fadeIn_Content">
        Your friendly neighborhood frontend developer, UX architect, and
        JavaScript engineer. I spend my days (and often nights) painting the
        Internet canvas with <span class="font-bold">Projects</span> and lines
        of code, turning zeroes and ones into immersive, interactive
        experiences,
      </p>
      <p class="text-white text-2xl font-thin mb-10 fadeIn_Content">
        Bona fide photochromic <span class="font-bold">Lens</span> enthusiast -
        sunlight or indoors, I've got it covered. I tread the path of
        minimalism, finding beauty in simplicity and order. When I'm not
        crafting beautiful web experiences, you can find me reading
        <span class="font-bold">Articles</span> or swaying to the rhythm of Pop
        Music & Jazz, losing myself in the captivating flow of melodies. anyways
        you can <span class="font-bold">Contact Me</span>
      </p>
      <div class="flex">
        <p>See more about me</p>
        <p>→</p>
      </div>
    </div>
  </div>
</template>

<style>
.typed {
  color: white !important;
}

.fadeIn_Title {
  animation: fadeIn 3s;
}

.fadeIn_Content {
  animation: fadeIn 8s;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
