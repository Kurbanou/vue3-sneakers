<script setup>
import Header from './components/Header.vue'
import Cardlist from './components/Cardlist.vue'
import Drawer from './components/Drawer.vue'
</script>

<template>
  <Drawer />
  <div class="w-4/5 m-auto bg-white rounded-xl shadow-xl mt-14">
    <Header />
    <div class="p-10">
      <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>
      <Cardlist />
    </div>
  </div>
</template>

<style scoped></style>
