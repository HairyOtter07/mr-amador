<template>
  <div class="flex justify-between items-end px-12 py-10 w-full bg-gradient-to-r from-[#311B39]">
    <div class="flex space-x-11">
      <div class="flex flex-col space-y-2">
        <NuxtLink class="font-bold" to="/about">About</NuxtLink>
        <NuxtLink to="/about#the-mission">The Mission</NuxtLink>
        <NuxtLink to="/about#who-we-are">Who We Are</NuxtLink>
        <NuxtLink to="/about#how-it-started">How it Started</NuxtLink>
        <NuxtLink to="/about#2025-vision">20(25) Vision</NuxtLink>
      </div>
      <!-- <div class="flex flex-col space-y-2">
        <p class="font-bold">Alumni</p>
        <p>'23-'24 Boys</p>
        <p>'22-'23 Boys</p>
        <p>Archive</p>
      </div> -->
      <div class="flex flex-col space-y-2">
        <NuxtLink class="font-bold" to="/boys">Boys</NuxtLink>
        <NuxtLink to="/boys#directors">Directors</NuxtLink>
        <NuxtLink to="/boys#seniors">Seniors</NuxtLink>
        <NuxtLink to="/boys#juniors">Juniors</NuxtLink>
        <NuxtLink to="/boys#sophomores">Sophomores</NuxtLink>
      </div>
    </div>
    <div class="flex flex-col space-y-3 items-end">
      <div class="flex space-x-5">
        <NuxtLink to="">
          <Icon icon="ion:logo-x" class="w-14 h-14" />
        </NuxtLink>
        <NuxtLink to="">
          <Icon icon="ion:logo-instagram" class="w-14 h-14" />
        </NuxtLink>
        <NuxtLink to="">
          <Icon icon="ion:logo-github" class="w-14 h-14" />
        </NuxtLink>
      </div>
      <div class="flex flex-col items-end">
        <p>Designed with care by Hunter Selkow and Joshua Antony</p>
        <p>Brought to life by Vardaan Singhania</p>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">
import { Icon } from '@iconify/vue';
</script>