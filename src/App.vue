<template>
  <div class="min-h-screen flex flex-col">
    <Header />
    <main class="flex-grow ml-48">
      <div class="p-6">
        <router-view />
      </div>
    </main>
    <Footer class="ml-48" />
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>
