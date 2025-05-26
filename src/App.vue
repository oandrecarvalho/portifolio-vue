<script setup>
import Navbar from './components/NavbarComponent.vue'
import Footer from './components/FooterComponent.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <Navbar />

    <div class="flex-grow flex flex-col">
      <router-view></router-view>
    </div>

    <Footer />
  </div>
</template>