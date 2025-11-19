<template>
  <div class="bg-[#ffeddd] w-full h-screen min-w-[300px]">
    <!-- 헤더 -->
    <div class="relative">
      <!-- 헤더 이미지 -->
      <img class="w-full opacity-80 max-h-[250px]" src="/headerbg.png" alt="headerBG" />
      <!-- 로고 이미지 동그랗게 -->
      <img
        class="w-[25%] max-w-[140px] rounded-full absolute left-1/2 bottom-0 -translate-x-1/2 translate-y-1/2"
        src="/image.png"
        alt="logo" />
    </div>
    <div class="flex flex-col gap-3 text-center mt-18 md:mt-25">
      <!-- 상호명 -->
      <p class="font-semibold text-xl md:text-2xl text-[#194d29]">Leaf Art Studio</p>
      <!-- 간단 소개 -->
      <p class="text-[#194d29]">삼덕동 그림 공방 리프아트스튜디오입니다.</p>
    </div>
    <!-- 링크 버튼들 -->
    <div class="flex flex-col gap-4 items-center mt-10 md:mt-17">
      <!-- 인스타그램 -->
      <a
        target="_blank"
        class="border-2 w-[200px] block py-2 text-center rounded-full border-[#194d29] text-[#194d29] font-bold hover:bg-[#194d29] hover:text-[#ffeddd]"
        href="https://www.instagram.com/leaf.art_studio/#">
        인스타그램
      </a>
      <!-- 네이버 플레이스 -->
      <a
        target="_blank"
        class="border-2 w-[200px] block py-2 text-center rounded-full border-[#194d29] text-[#194d29] font-bold hover:bg-[#194d29] hover:text-[#ffeddd]"
        href="https://naver.me/GmtRyCsS">
        네이버 플레이스
      </a>
      <!-- 카카오톡 -->
      <a
        target="_blank"
        class="border-2 w-[200px] block py-2 text-center rounded-full border-[#194d29] text-[#194d29] font-bold hover:bg-[#194d29] hover:text-[#ffeddd]"
        href="http://pf.kakao.com/_ExiSxcn">
        카카오톡
      </a>
    </div>
  </div>
</template>

<script setup></script>
