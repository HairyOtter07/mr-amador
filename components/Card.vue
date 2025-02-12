<template>
  <div class="flex flex-col py-12 px-16 w-full space-y-16 items-center bg-zinc-900 rounded-2xl">
    <h1 class="font-semibold text-center bg-gradient-to-r from-[#44afc7] to-[#d294e7] text-3xl text-transparent bg-clip-text">{{ heading }}</h1>
    <Icon :icon="icon" width="76" height="76" />
    <p class="text-center text-lg font-semibold">
      <slot />
    </p>
  </div>
</template>
<script setup lang="ts">
import { Icon } from '@iconify/vue';

defineProps<{
  heading: string;
  icon: string;
}>();
</script>