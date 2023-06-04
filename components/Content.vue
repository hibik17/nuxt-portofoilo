<script setup>
import { VueTyper } from "vue-typer";
</script>

<template>
  <div class="text-white">
    <div class="w-[70%] mx-auto">
      <vue-typer
        text="NICE TO MEET YOU I'M HIBIKI"
        class="flex justify-start text-3xl font-mono typed typed typed mt-10 mb-10 fadeIn_Title"
        repeat="3"
        caret-animation="smooth"
      ></vue-typer>
      <p class="text-white text-xl font-thin mb-10 fadeIn fadeIn_content">
        Your friendly neighborhood frontend developer, UX architect, and
        JavaScript engineer. I spend my days (and often nights) painting the
        Internet canvas with
        <span class="font-bold">Projects</span> and lines of code, turning
        zeroes and ones into immersive, interactive experiences,
      </p>
      <p class="text-white text-2xl font-thin mb-10 fadeIn_content">
        Bona fide photochromic <span class="font-bold">Lens</span> enthusiast -
        sunlight or indoors, I've got it covered. I tread the path of
        minimalism, finding beauty in simplicity and order. When I'm not
        crafting beautiful web experiences, you can find me reading
        <span class="font-bold">Articles</span> or swaying to the rhythm of Pop
        Music & Jazz, losing myself in the captivating flow of melodies. anyways
        you can <span class="font-bold">Contact Me</span>
      </p>
      <div class="flex fadeIn_content mb-10">
        <p class="animate-bounce">See more about me</p>
        <img
          src="../src/images/共有矢印.png"
          alt="yajirushi"
          class="w-6 h-6 white_img ml-5 animate-bounce"
        />
      </div>
      <div class="w-[30%] mx-auto fadeIn_content">
        <ul class="flex justify-between">
          <li>
            <a href="https://github.com/hibik17">
              <img
                src="../src/images/github-mark.png"
                alt="github"
                class="white_logo"
              />
            </a>
          </li>
          <li>
            <a href="https://www.wantedly.com/id/hibiki_tatsu">
              <img
                src="../src/images/Wantedly_Mark_Blk.png"
                alt="wantedly"
                class="white_logo"
              />
            </a>
          </li>
          <li>
            <a href="https://www.instagram.com/___hbk17/">
              <img
                src="../src/images/Instagram_Glyph_Black.png"
                alt="instagram"
                class="white_logo"
              />
            </a>
          </li>
        </ul>
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

.fadeIn_content {
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

.white_logo {
  filter: invert(88%) sepia(61%) saturate(0%) hue-rotate(229deg)
    brightness(107%) contrast(101%);
  width: 50px;
  height: 50px;
}
</style>
