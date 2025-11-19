<template>
  <div class="bg-[#ffeddd] w-full h-screen min-w-[300px]">
    <!-- 헤더 -->
    <div class="relative">
      <!-- 헤더 이미지 -->
      <img class="w-full opacity-80 max-h-[300px]" src="/headerbg.jpg" alt="headerBG" />
      <!-- 로고 이미지 동그랗게 -->
      <img
        class="w-[25%] max-w-[140px] rounded-full absolute left-1/2 bottom-0 -translate-x-1/2 translate-y-1/2"
        src="/image.png"
        alt="logo" />
    </div>
    <div class="flex flex-col gap-3 text-center mt-18 md:mt-25">
      <!-- 상호명 -->
      <p class="font-semibold text-base md:text-2xl">Leaf Art Studio</p>
      <!-- 간단 소개 -->
      <p>삼덕동 그림 공방 리프아트스튜디오입니다.</p>
    </div>
    <!-- 링크 버튼들 -->
    <div class="flex flex-col gap-4 items-center mt-10 md:mt-17">
      <!-- 인스타그램 -->
      <a class="border-2 py-2 px-6 rounded-full border-[#194d29] text-[#194d29] font-bold" href="">
        인스타그램
      </a>
      <!-- 네이버 플레이스 -->
      <!-- 카카오톡 -->
    </div>
  </div>
</template>

<script setup></script>

<!-- .wrap {
   margin: auto;
   width: 100%;
   height: 100vh;
   background-color: #fbe3ce;
   color: #194d29;
 } -->
