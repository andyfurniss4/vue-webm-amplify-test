<script setup>
//import TheWelcome from '@/components/TheWelcome.vue'
</script>

<template>
  <main>
    <h2>Local asset (../assets/big-buck-bunny_trailer.webm)</h2>
    <video playsinline autoplay muted loop style="border:1px solid black;">
      <source src="../assets/big-buck-bunny_trailer.webm" width="311" height="600" type="video/webm" />
      Your browser does not support the video tag.
    </video>
    <h2>Web reference (https://dl8.webmfiles.org/big-buck-bunny_trailer.webm)</h2>
    <video playsinline autoplay muted loop style="border:1px solid black;">
      <source src="https://dl8.webmfiles.org/big-buck-bunny_trailer.webm" width="400" type="video/webm" />
      Your browser does not support the video tag.
    </video>
  </main>
</template>
