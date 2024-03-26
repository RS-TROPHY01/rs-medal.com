<script setup lang="ts">
const title = "RS MEDAL | โล่รางวัลคริสตัล โล่อะคริลิค คุณภาพดีแข็งแรงทนทาน";
const description =
  "บริษัทจัดจำหน่ายโล่รางวัลคุณภาพดีแข็งแรงทนทาน มีให้เลือกทั้งโล่รางวัลคริสตัล โล่รางวัลอะคริลิค โดยเรามีทั้งในรูปแบบหน้าร้านและออนไลน์พร้อมบริการจัดส่งทั่วประเทศไทย";
const image = "/panel/hero_section.webp";
useSeoMeta({
  title: title,
  ogTitle: title,
  twitterTitle: title,
  description: description,
  ogDescription: description,
  twitterDescription: description,
  ogImage: image,
  twitterImage: image,
  keywords:
    "RS MEDAL, โล่รางวัล, โล่คริสตัล, โล่รางวัลคริสตัล, โล่อะคริลิค, โล่รางวัลอะคริลิค",
});
</script>
<template>
  <div>
    <AppHeroSection />
    <div class="grid md:grid-cols-2">
      <div>
        <div class="text-center pt-4">
          <div>
            <h1>เหรียญรางวัล</h1>
            <ul>
              <li>&#127941;ไม่มีค่าออกแบบ&#127941;</li>
              <li>&#127941;แนะนำในการออกแบบได้&#127941;</li>
              <li>&#127941;สีคมชัดแข็งแรงไม่ขึ้นสนิม&#127941;</li>
              <li>&#127941;ใช้เวลาในการผลิตตามจำนวนที่สั่ง&#127941;</li>
            </ul>
          </div>
        </div>
        <div>
          <img src="/panel/line.webp" alt="" />
        </div>
      </div>
      <div class="mx-auto">
        <img src="/panel/medal.webp" height="500px" width="500px" alt="" />
      </div>
    </div>
    <AppPrice />
    <div class="grid md:grid-cols-2">
      <div class="p-2">
        <img src="/panel/medal2.webp" height="500px" width="500px" alt="" />
      </div>
      <div class="text-center p-2">
        <h2>&#127941;เหรียญรางวัลซิงค์อัลลอย&#127941;</h2>
        <ul class="text-left px-8">
          <li>&#10004;ไม่เกิดสนิม</li>
          <li>&#10004;ทำให้ดูมีมิติได้</li>
          <li>&#10004;ขึ้นบล๊อกด้วยโลหะ</li>
          <li>&#10004;มีความคมชัดสูงเรียบเนียน</li>
          <li>&#10004;ลงไม่จำกัดสีด้วย UV ไล่เฉดสีได้</li>
        </ul>
        <h2>&#127941;เหรียญรางวัลตะกั่ว&#127941;</h2>
        <ul class="text-left px-8">
          <li>&#10006;มีน้ำหนักมาก</li>
          <li>&#10006;ขึ้นบล๊อกด้วยยาง</li>
          <li>&#10006;ไม่มีมิติเท่างานซิงค์อัลลอย</li>
          <li>&#10006;ลงสีได้แค่ 3-4 สี เกิดสนิมได้</li>
        </ul>
      </div>
    </div>
    <AppOurCustomer />
  </div>
</template>
