<template>
  <div class="w-full">
    <NavBar current-page="boys" />
    <div class="flex flex-col w-full px-20 py-20 space-y-20 items-center">
      <h1 class="font-bold text-8xl">Meet The <span class="text-[#d294e7]">Boys</span></h1>
      <div id="directors" class="flex flex-col w-full items-center space-y-10">
        <h1 class="font-bold text-7xl w-full text-start">Directors</h1>
        <div class="flex flex-row w-full items-center justify-center space-x-16">
          <Boy name="Taylor Cohn" grade="d" />
          <Boy name="MaKenzie Glenn" grade="d" />
          <Boy name="Hunter Selkow" grade="d" />
        </div>
      </div>
      <div id="seniors" class="flex flex-col w-full items-center space-y-10">
        <h1 class="font-bold text-7xl w-full text-start">Seniors</h1>
        <div class="flex flex-row w-full items-center justify-center space-x-16">
          <Boy name="Ryan Doan" grade="12" />
          <Boy name="Kevin Lee" grade="12" />
          <Boy name="Wyatt Loos" grade="12" />
        </div>
        <div class="flex flex-row w-full items-center justify-center space-x-16">
          <Boy name="Nishant Nayak" grade="12" />
          <Boy name="Paul Ti'a" grade="12" />
        </div>
      </div>
      <div id="juniors" class="flex flex-col w-full items-center space-y-10">
        <h1 class="font-bold text-7xl w-full text-start">Juniors</h1>
        <div class="flex flex-row w-full items-center justify-center space-x-16">
          <Boy name="Nathan Marek" grade="11" />
          <Boy name="Rayyan Shah" grade="11" />
          <Boy name="Gavin Whalley" grade="11" />
        </div>
      </div>
      <div id="sophomores" class="flex flex-col w-full items-center space-y-10">
        <h1 class="font-bold text-7xl w-full text-start">Sophomores</h1>
        <div class="flex flex-row w-full items-center justify-center space-x-16">
          <Boy name="Oliver Heid" grade="10" />
          <Boy name="Logan Jew-Fortner" grade="10" />
        </div>
      </div>
    </div>
    
    <Footer />
  </div>
</template>
<script setup lang="ts">

</script>