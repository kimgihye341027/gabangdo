<script setup>
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";
import Content1 from "./views/Content1.vue";
import Content2 from "./views/Content2.vue";
import Content3 from "./views/Content3.vue";
import Visual from "./views/Visual.vue";
import Modal from "./views/Modal.vue";
</script>

<template>
  <div class="wrap">
    <Header />
    <main>
      <Visual />
      <Content1 />
      <Content2 />
      <Content3 />
      <Modal />
      <router-view />
    </main>
    <!-- <Footer /> -->
  </div>
</template>

<style scoped></style>
