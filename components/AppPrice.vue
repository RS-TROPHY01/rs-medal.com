<template>
  <div class="grid md:grid-cols-2">
    <div class="text-center">
      <h2>&#127941;ราคาเหรียญรางวัลซิงค์อัลลอย&#127941;</h2>
      <ul>
        <li>ขั้นต่ำ 100 เหรียญ/ผลิต 30-45 วัน</li>
        <li>ขนาดมาตรฐาน 6.5 ซม. หนา 3.5-4 มม.</li>
        <li>พิมพ์สีด้วย UV ได้ไม่จำกัด/ปั้นนูน 3 มิติ</li>
        <li>สายพิมพ์ซับลิเมชั่น/ขนาด 2.5 ซม.</li>
      </ul>
      <div>
        <h2>จำนวน/ราคากลาง</h2>
        <table class="mx-auto">
          <thead>
            <tr>
              <th
                class="px-4 py-2 bg-gray-200 text-gray-700 font-bold uppercase text-sm leading-normal"
              >
                &#127941;จำนวนเหรียญ&#127941;
              </th>
              <th
                class="px-4 py-2 bg-gray-200 text-gray-700 font-bold uppercase text-sm leading-normal"
              >
                <span class="text-green-600">฿</span> ราคา/เหรียญ
                <span class="text-green-600">฿</span>
              </th>
              <th
                class="px-4 py-2 bg-gray-200 text-gray-700 font-bold uppercase text-sm leading-normal"
              >
                <span class="text-green-600">฿</span> ค่าบล็อก
                <span class="text-green-600">฿</span>
              </th>
            </tr>
          </thead>
          <tbody>
            <tr
              v-for="(row, rowIndex) in rows"
              :key="rowIndex"
              class="border-b border-gray-200"
            >
              <td
                v-for="(cell, cellIndex) in row"
                :key="cellIndex"
                :class="{ 'text-green-500': cell === 'ฟรี' }"
                class="px-4 py-2 text-sm leading-normal"
              >
                {{ cell }}
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <div>
      <img src="/panel/medal1.webp" height="500px" width="500px" alt="" />
    </div>
  </div>
</template>

<script lang="ts" setup>
const rows = [
  ["100", "150", "5,500"],
  ["101-300", "120-130", "5,500"],
  ["301-500", "85-95", "5,500"],
  ["501-1,000", "60-65", "5,500"],
  ["1,001-2,000", "50-55", "ฟรี"],
  ["2,001-5,000	", "45-50", "ฟรี"],
  ["5,000 ขึ้นไป", "40-45", "ฟรี"],
];
</script>

<style></style>
