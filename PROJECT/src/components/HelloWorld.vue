<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

</script>

<template>
  <div class="image-container">
  <img src="/Gamecube.jpeg" alt="GameCube">
<p>
  GameCube (2001): Nintendo's compact, cube-shaped console featured 
  innovative mini-discs, strong first-party exclusives like Super Smash Bros. Melee, and 
  a unique controller design but struggled against the PS2 and Xbox in sales.
</p>
  <img src="/PS4.jpeg" alt="PS4">
  <p>
    PlayStation 4 (2013): Sonys highly successful console emphasized 
    powerful hardware, an extensive game library, and strong online features, leading 
    to over 117 million units sold and defining modern gaming with titles 
    like God of War and The Last of Us Part II.
  </p>
  <img src="/SNES.jpeg" alt="SNES">
  <p>
    Super Nintendo Entertainment System (SNES) (1990/1991): This 16-bit 
    powerhouse delivered iconic games like Super Mario World 
    and The Legend of Zelda: A Link to the Past, revolutionizing home 
    gaming with improved graphics, sound, and deeper gameplay experiences.
  </p>
  <img src="/Wii.jpeg" alt="Wii">
  <p>
    Wii (2006): Nintendo’s motion-controlled console became a cultural 
    phenomenon with accessible, family-friendly games like Wii Sports, selling 
    over 100 million units despite weaker hardware compared to competitors.
  </p>
  <img src="/Xbox360.jpeg" alt="Xbox360">
  <p>
    Xbox 360 (2005): Microsoft's second console pioneered online multiplayer 
    with Xbox Live, introduced achievements, and boasted a strong library with
    Halo 3 and Gears of War, but suffered from hardware failures like the infamous "Red Ring of Death."
  </p>
  </div>
</template>
<style scoped>
.image-container img {
  margin: 10px;
  padding: 5px;
  width: 200px; 
}
</style>
<style scoped>
.read-the-docs {
  color: #888;
}
</style>
