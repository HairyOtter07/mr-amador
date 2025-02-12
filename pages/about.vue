<template>
  <div class="w-full">
    <NavBar current-page="about" class="absolute z-10" />
    <div class="relative w-full h-full">
      <img src="~/assets/images/about/hero.png" class="w-full h-full" />
      <div class="absolute top-[50%] -translate-y-[50%] flex flex-row justify-end w-full px-20">
        <div class="flex flex-col space-y-5">
            <h1 class="font-bold text-9xl text-[#e49bff]">
              Better<br>Care.
            </h1>
            <h1 class="font-bold text-9xl">
              Brighter<br>Future.
            </h1>
        </div>
      </div>
    </div>
    <div class="flex flex-col w-full items-center py-20 space-y-16">
      <div class="flex flex-row w-full px-20 space-x-20">
        <Card id="how-it-started" heading="How It Started" icon="twemoji:rocket">
          Mr. Amador began in 2004 as a small group dedicated to raising money for the George Marks Children's House in San Leandro, California.
        </Card>
        <Card id="who-we-are" heading="Who We Are" icon="twemoji:magnifying-glass-tilted-right">
          Mr. Amador is comprised of ten highly motivated boys who have been nominated by peers and teachers. They are expected to attend numerous fundraisers, perform dances, and embody respect and compassion.
        </Card>
        <Card id="the-mission" heading="The Mission" icon="twemoji:light-bulb">
          The Mr. Amador SHOW is the program's magnum opus. The boys each perform a skit relating to the theme of the show. In the past the show's themes have been music genres, movies, and superheroes.
        </Card>
      </div>
      <NuxtLink to="https://georgemark.org/" class="font-mono text-[#e49bff] underline font-semibold text-2xl flex flex-row items-center space-x-2">
        <p>
          Learn more about George Marks Children's House 
        </p>
        <Icon icon="majesticons:open" />
      </NuxtLink>
    </div>
    <div id="2025-vision" class="relative flex flex-col w-full items-center py-24 px-20">
      <h1 class="text-8xl font-bold">20<span class="text-[#d294e7]">{25}</span> VISION</h1>
      <div class="flex flex-row justify-between w-full items-center">
        <img src="~/assets/images/about/left-hunter.png" />
        <img src="~/assets/images/about/right-josh.png" />
      </div>
      <p class="absolute top-96 text-2xl text-center border-[#d294e7] border-4 font-semibold p-4 rounded-3xl max-w-lg">
        This year we are working harder than ever to build new fundraisers from the ground up to create an interactive experience for the Mr. Amador program and the community. Follow our socials to see what we plan to do this year and stay updated on everything Mr. Amador.
      </p>
    </div>
    <Footer />
  </div>
</template>
<script setup lang="ts">
import { Icon } from '@iconify/vue';
</script>