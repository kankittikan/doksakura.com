<template>
  <audio src="/sound/click1.wav" id="s"/>
  <header class="bg-gradient-to-r from-pink-500 to-purple-500 flex h-16">
    <div class="w-10 my-auto ml-3">
      <img src="/favicon.ico" />
    </div>
    <NuxtLink to="./" class="text-white px-2 ml-4 hover:bg-pink-400 py-5" @click="playSound">Home</NuxtLink>
    <NuxtLink to="minecraft" class="text-white px-2 hover:bg-pink-400 py-5" @click="playSound">Minecraft</NuxtLink>
    <NuxtLink to="space" class="text-white px-2 hover:bg-pink-400 py-5" @click="playSound">Space</NuxtLink>
    <NuxtLink to="https://access.doksakura.com" target="_blank" class="text-white px-2 hover:bg-pink-400 py-5" @click="playSound">Access</NuxtLink>
    <NuxtLink to="https://content.doksakura.com" target="_blank" class="text-white px-2 hover:bg-pink-400 py-5" @click="playSound">Content</NuxtLink>

  </header>
</template>  

<script lang="ts" setup>
  const playSound = () => {
    var audio1 = document.getElementById("s");
    audio1.play();
  }
</script>