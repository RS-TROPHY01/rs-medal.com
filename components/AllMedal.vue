<template>
  <div class="grid grid-cols-5">
    <div v-for="image in images" :key="image.src">
      <img
        :src="'/panel/' + image.src + '.webp'"
        class="w-full h-auto rounded-none"
        alt="เหรียญรางวัล"
        title="เหรียญรางวัล"
        ariaLabel="เหรียญรางวัล"
      />
    </div>
  </div>
</template>

<script lang="ts" setup>
const images = [
  { src: "1", alt: "" },
  { src: "2", alt: "" },
  { src: "3", alt: "" },
  { src: "4", alt: "" },
  { src: "5", alt: "" },
  { src: "6", alt: "" },
  { src: "7", alt: "" },
  { src: "8", alt: "" },
  { src: "9", alt: "" },
  { src: "10", alt: "" },
  { src: "11", alt: "" },
  { src: "12", alt: "" },
  { src: "13", alt: "" },
];
</script>
