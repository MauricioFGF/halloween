<script setup>
import "./styles.scss";
import { createScrollRevealDirective } from "vue-scroll-reveal";
const vScrollReveal = createScrollRevealDirective({
  origin: "top",
  distance: "60px",
  duration: 2000,
  delay: 200,
});
</script>

<template>
  <section class="section discount" id="desconto">
    <div class="discount__container container grid">
      <div class="discount__data" v-scroll-reveal="{ origin: 'right' }">
        <h2 class="discount__title">
          50% de desconto <br />
          em novos produtos
        </h2>
        <a href="#" class="button">Ofertas</a>
      </div>

      <img
        v-scroll-reveal="{ origin: 'left' }"
        src="../../assets/img/discount-img.png"
        alt=""
        class="discount__img"
      />
    </div>
  </section>
</template>
