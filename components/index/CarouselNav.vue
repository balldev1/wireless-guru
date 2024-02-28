<template>
  <UCarousel v-slot="{ item }" :items="items" :ui="{ item: 'basis-full' }" class="rounded-lg overflow-hidden" arrows>
    <img :src="currentImage" class="w-full h-[20dvw]" draggable="false">
  </UCarousel>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>

<script setup lang="ts">
import { ref, onMounted, onBeforeUnmount } from 'vue';
import LogoRoute from "~/components/index/LogoRoute.vue";

const items = [
  'https://picsum.photos/1920/1080?random=1',
  'https://picsum.photos/1920/1080?random=2',
  'https://picsum.photos/1920/1080?random=3',
  'https://picsum.photos/1920/1080?random=4',
  'https://picsum.photos/1920/1080?random=5',
  'https://picsum.photos/1920/1080?random=6'
];

const currentIndex = ref(0);

onMounted(() => {
  // เปลี่ยนรูปภาพทุกๆ 1 วินาที เมื่อ component ถูกเรียกใช้งานใน browser
  const intervalId = setInterval(() => {
    currentIndex.value = (currentIndex.value + 1) % items.length;
  }, 3000);

  // ยกเลิก setInterval เมื่อ component ถูกทำลายเพื่อป้องกันการทิ้งลูกศร
  onBeforeUnmount(() => {
    clearInterval(intervalId);
  });
});

const currentImage = computed(() => {
  return items[currentIndex.value];
});
</script>