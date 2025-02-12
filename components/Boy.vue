<template>
  <div class="relative flex flex-col space-y-0 bg-zinc-900 rounded-2xl items-center max-w-56 overflow-clip">
    <img :src="images[`/assets/images/boys/${fname}`]"  class="h-full" />
    <h1 class="py-6 w-full text-center text-3xl font-semibold absolute bottom-0 bg-zinc-900/80 px-1">
      {{ firstName }} <span class="whitespace-nowrap">{{ lastName }}</span>
    </h1>
  </div>
</template>
<script setup lang="ts">
const props = defineProps<{
  name: string;
  grade: string;
}>();

const firstName = computed(() => props.name.split(" ")[0])
const lastName = computed(() => props.name.split(" ")[1])
const fname = computed(() => `${props.grade}_${props.name.split(" ").join("_").toLowerCase()}.jpeg`);

const glob = import.meta.glob('@/assets/images/boys/*.jpeg', { eager: true })
const images = Object.fromEntries(
  Object.entries(glob).map(([key, value]) => [key, value.default])
)
</script>