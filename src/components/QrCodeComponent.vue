<script setup>
import imageQR from '@/assets/images/image-qr-code.png'
</script>
<template>
  <article>
    <div class="container">
    <header>
      <img :src="imageQR" alt="image QR code" />
      <h1>Improve your front-end skills by building projects</h1>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </header>
  </div>
   <footer>
      <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded
      by <a href="https://github.com/cornelio-ii/Qr-code-component" target="_blank">Cornelio Llagas</a>.
    </div>
  </footer>
  </article>
  
</template>
