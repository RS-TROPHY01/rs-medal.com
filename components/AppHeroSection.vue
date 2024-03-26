<template>
  <div class="relative h-full">
    <img
      src="/panel/hero_section.webp"
      class="w-full h-auto rounded-b-none"
      alt="RS MEDAL PANEL"
      title="RS MEDAL PANEL"
      aria-label="RS MEDAL PANEL"
      width="1134px"
      height="327px"
    />
    <div class="grid grid-cols-4">
      <div v-for="image in images" :key="image.id">
        <img
          :src="image.src"
          class="w-full h-auto rounded-none"
          alt="เหรียญรางวัล"
          title="เหรียญรางวัล"
          ariaLabel="เหรียญรางวัล"
        />
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
const images = [
  {
    id: 1,
    src: "/panel/1.webp",
  },
  {
    id: 2,
    src: "/panel/2.webp",
  },
  {
    id: 3,
    src: "/panel/3.webp",
  },
  {
    id: 4,
    src: "/panel/4.webp",
  },
];
</script>
