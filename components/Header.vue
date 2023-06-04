<script setup></script>

<template>
  <div class="w-[80%] m-auto h-32 flex mb-10">
    <nuxt-link to="/" class="m-6 w-auto">
      <img src="../src/images/diamond.png" class="w-10 h-10 white_img" />
    </nuxt-link>
    <div class="m-6 w-full flex justify-end">
      <ul class="flex text-white font-bold align-middle">
        <li class="mr-6 leading-10">About</li>
        <li class="mr-6 leading-10">Projects</li>
        <li class="mr-6 leading-10">Contact</li>
        <li>
          <img
            src="../src/images/dark-mode.png"
            alt="dark mode"
            class="w-10 h-10 white_img"
          />
        </li>
      </ul>
    </div>
  </div>
</template>

<style>
.white_img {
  filter: invert(88%) sepia(61%) saturate(0%) hue-rotate(229deg)
    brightness(107%) contrast(101%);
}
</style>
