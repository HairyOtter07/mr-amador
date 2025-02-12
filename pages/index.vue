<template>
  <div class="w-full">
    <NavBar current-page="home" class="absolute z-10" />
    <div class="relative bg-gradient-radial-from-br from-[#8a4c9f]/60 to-black">
      <img src="~/assets/images/home/hero.png" class="w-full h-full" />
      <div class="absolute top-[50%] -translate-y-[50%] flex flex-row justify-between w-full px-20">
        <h1 class="font-bold text-9xl bg-gradient-to-br from-white to-[#8a4c9f] text-transparent bg-clip-text">
          For<br>The<br>House.
        </h1>
      </div>
    </div>
    <div class="flex flex-col w-full px-20 py-12 bg-gradient-to-br from-black via-zinc-900 to-black">
      <div class="flex flex-row justify-between w-full items-center">
        <NuxtLink to="https://www.chick-fil-a.com">
          <img src="~/assets/images/home/sponsors/chickfila.png" class="scale-75" />
        </NuxtLink>
        <NuxtLink to="https://www.castlewoodcc.org">
          <img src="~/assets/images/home/sponsors/castlewood.png" class="scale-75" />
        </NuxtLink>
        <NuxtLink to="https://amador.pleasantonusd.net">
          <img src="~/assets/images/home/sponsors/avhs.png" class="scale-75" />
        </NuxtLink>
        <NuxtLink to="https://www.themeadowlarkdairy.com">
          <img src="~/assets/images/home/sponsors/meadowlark.png" class="scale-75" />
        </NuxtLink>
        <NuxtLink to="https://www.athletics.com">
          <img src="~/assets/images/home/sponsors/athletics.png" class="scale-75" />
        </NuxtLink>
        <NuxtLink to="https://www.sidetrackeats.com">
          <img src="~/assets/images/home/sponsors/sidetrack.png" class="scale-75" />
        </NuxtLink>
      </div>
      <div class="flex flex-col w-full px-20 py-36 space-y-20">
        <div class="font-semibold flex flex-row w-full px-24 justify-between items-center">
          <div class="flex flex-col items-center">
            <h1 class="text-7xl bg-gradient-to-b from-[#336683] to-[#8a4c9f] text-transparent bg-clip-text">33</h1>
            <p class="text-3xl">dedicated students</p>
          </div>
          <div class="flex flex-col items-center">
            <h1 class="text-7xl bg-gradient-to-b from-[#8a4c9f] to-[#336683] text-transparent bg-clip-text">20</h1>
            <p class="text-3xl">years in production</p>
          </div>
        </div>
        <div class="font-semibold flex flex-col items-center">
          <h1 class="text-9xl bg-gradient-to-r from-[#d573f6] to-[#59a6d5] text-transparent bg-clip-text">$1M+</h1>
          <p class="text-3xl">raised</p>
        </div>
      </div>
    </div>
    <div class="flex flex-col w-full px-40 py-40">
      <div class="flex flex-row w-full justify-between items-center">
        <h1 class="font-bold text-8xl">THE</h1>
        <img src="~/assets/images/home/change/change1-1.png" class="scale-75" />
        <img src="~/assets/images/home/change/change1-2.png" class="scale-75" />
        <img src="~/assets/images/home/change/change1-3.png" class="scale-75" />
        <img src="~/assets/images/home/change/change1-4.png" class="scale-75" />
      </div>
      <div class="flex flex-row w-full justify-between items-center">
        <img src="~/assets/images/home/change/change2-1.png" class="scale-75" />
        <img src="~/assets/images/home/change/change2-2.png" class="scale-75" />
        <img src="~/assets/images/home/change/change2-3.png" class="scale-75" />
        <h1 class="font-bold text-8xl pr-8">CHANGE</h1>
      </div>
      <div class="flex flex-row w-full justify-between items-center">
        <h1 class="font-bold text-8xl">STARTS</h1>
        <img src="~/assets/images/home/change/change3-1.png" class="scale-75" />
        <img src="~/assets/images/home/change/change3-2.png" class="scale-75" />
        <img src="~/assets/images/home/change/change3-3.png" class="scale-75" />
      </div>
      <div class="flex flex-row w-full justify-between items-center">
        <img src="~/assets/images/home/change/change4-1.png" class="scale-75" />
        <img src="~/assets/images/home/change/change4-2.png" class="scale-75" />
        <img src="~/assets/images/home/change/change4-3.png" class="scale-75" />
        <h1 class="font-bold text-8xl">WITH</h1>
        <img src="~/assets/images/home/change/change4-4.png" class="scale-75" />
      </div>
      <div class="flex flex-row w-full justify-between items-center">
        <img src="~/assets/images/home/change/change5-1.png" class="scale-75" />
        <h1 class="font-bold text-8xl">YOU</h1>
        <img src="~/assets/images/home/change/change5-2.png" class="scale-75" />
        <img src="~/assets/images/home/change/change5-3.png" class="scale-75" />
        <img src="~/assets/images/home/change/change5-4.png" class="scale-75" />
      </div>
    </div>
    <Footer />
  </div>
</template>
<script setup lang="ts">
useHead({
  title: "Home",
});
</script>