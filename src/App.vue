<script setup>
import Header from "./components/Header/Header.vue";
import Home from "./components/Home/Home.vue";
import Category from "./components/Category/Category.vue";
import About from "./components/About/About.vue";
import Trick from "./components/Trick/Trick.vue";
import Discount from "./components/Discount/Discount.vue";
import Arrivals from "./components/Arrivals/Arrivals.vue";
import Newsletter from "./components/Newsletter/Newsletter.vue";
import Footer from "./components/Footer/Footer.vue";
import { createScrollRevealDirective } from "vue-scroll-reveal";
const vScrollReveal = createScrollRevealDirective({
  origin: "bottom",
  distance: "60px",
  duration: 2000,
  delay: 400,
});
</script>

<template>
  <Header />
  <main class="main">
    <Home v-scroll-reveal />
    <Category v-scroll-reveal />
    <About v-scroll-reveal />
    <Trick v-scroll-reveal />
    <Discount v-scroll-reveal />
    <Arrivals v-scroll-reveal />
    <Newsletter v-scroll-reveal />
  </main>
  <Footer v-scroll-reveal />
  <a href="#" class="scrollup" id="scroll-up">
    <i class="bx bx-up-arrow-alt scrollup__icon"></i>
  </a>
</template>

<style scoped></style>
