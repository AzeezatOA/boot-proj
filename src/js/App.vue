<script setup>
import Header from '../components/AppHeader.vue'
import Guides from '../components/AppGuides.vue'
import Footer from '../components/AppFooter.vue'
</script>

<template>
  <div class="container py-4 px-3 mx-auto">
    <Header />

    <h1>Build Bootstrap with Vue</h1>
    <div class="col-lg-8 px-0">
      <p class="fs-xl">Azeezat's version of Bootstrap with Vue.</p>
      <p>Hosted on Amplify</p>
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Machu_Picchu%2C_2023_%28012%29.jpg?utm_source=en.wikipedia.org&utm_campaign=index&utm_content=original" width="500" height="500">
    </div>

    <p>This is Machu Picchu. I hope to make it there someday before it is closed.</p>

    

    <hr class="col-1 my-5 mx-0">


    <Footer />
  </div>
</template>
