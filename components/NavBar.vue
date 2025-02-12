<template>
  <div class="flex justify-between items-center py-4 text-lg px-28 w-full">
    <NuxtLink to="/">
      <img src="~/assets/images/logo.png" />
    </NuxtLink>
    <div class="font-semibold flex items-center space-x-24">
      <NuxtLink :class="currentPage == 'home' && 'font-bold text-[#C78CDA]'" to="/">Home</NuxtLink>
      <NuxtLink :class="currentPage == 'about' && 'font-bold text-[#C78CDA]'" to="/about">About</NuxtLink>
      <!-- <NuxtLink :class="currentPage == 'alumni' && 'font-bold text-[#C78CDA]'" to="/alumni">Alumni</NuxtLink> -->
      <NuxtLink :class="currentPage == 'boys' && 'font-bold text-[#C78CDA]'" to="/boys">Boys</NuxtLink>
    </div>
    <div class="rounded-2xl border-[#8A4C9F] border px-3 py-1">
      <NuxtLink to="https://connect.clickandpledge.com/Organization/georgemarkchildrensfund/campaign/mramador2025" target="_blank">Donate</NuxtLink>
    </div>
  </div>
</template>
<script setup lang="ts">
defineProps<{
  currentPage: string;
}>();
</script>