<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Pagination, Navigation, Autoplay } from "swiper";
import "./styles.scss";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay, Navigation, Pagination],
    };
  },
};
</script>

<template>
  <section class="section new" id="novidades">
    <h2 class="section__title">Lançamentos</h2>

    <div class="new__container container">
      <Swiper
        loop
        :slidesPerView="3"
        mousewheel
        :pagination="{ clickable: true }"
        :autoplay="{
          delay: 3000,
          disableOnInteraction: false,
        }"
        :modules="modules"
        class="swiper new-swiper"
      >
        <SwiperSlide class="new__content">
          <div class="new__tag">Novo</div>
          <img src="../../assets/img/new1-img.png" alt="" class="new__img" />
          <h3 class="new__title">Casa Assombrada</h3>
          <span class="new__subtitle">Acessório</span>

          <div class="new__prices">
            <span class="new__price">R$69.99</span>
            <span class="new__discount">R$129.99</span>
          </div>

          <button class="button new__button">
            <i class="bx bx-cart-alt new__icon"></i>
          </button>
        </SwiperSlide>
        <SwiperSlide class="new__content swiper-slide">
          <div class="new__tag">Novo</div>
          <img src="../../assets/img/new2-img.png" alt="" class="new__img" />
          <h3 class="new__title">Velas de Halloween</h3>
          <span class="new__subtitle">Acessório</span>

          <div class="new__prices">
            <span class="new__price">R$23.99</span>
            <span class="new__discount">R$43.99</span>
          </div>

          <button class="button new__button">
            <i class="bx bx-cart-alt new__icon"></i>
          </button>
        </SwiperSlide>
        <SwiperSlide class="new__content swiper-slide">
          <div class="new__tag">Novo</div>
          <img src="../../assets/img/new3-img.png" alt="" class="new__img" />
          <h3 class="new__title">Chapéu de Bruxa</h3>
          <span class="new__subtitle">Acessório</span>

          <div class="new__prices">
            <span class="new__price">R$25.99</span>
            <span class="new__discount">R$39.99</span>
          </div>

          <button class="button new__button">
            <i class="bx bx-cart-alt new__icon"></i>
          </button>
        </SwiperSlide>
        <SwiperSlide class="new__content swiper-slide">
          <div class="new__tag">Novo</div>
          <img src="../../assets/img/new4-img.png" alt="" class="new__img" />
          <h3 class="new__title">Rip</h3>
          <span class="new__subtitle">Acessório</span>

          <div class="new__prices">
            <span class="new__price">R$34.99</span>
            <span class="new__discount">R$44.99</span>
          </div>

          <button class="button new__button">
            <i class="bx bx-cart-alt new__icon"></i>
          </button>
        </SwiperSlide>
        <SwiperSlide class="new__content swiper-slide">
          <div class="new__tag">Novo</div>
          <img src="../../assets/img/new5-img.png" alt="" class="new__img" />
          <h3 class="new__title">Bola de Cristal de caveira</h3>
          <span class="new__subtitle">Acessório</span>

          <div class="new__prices">
            <span class="new__price">R$25.99</span>
            <span class="new__discount">R$42.99</span>
          </div>

          <button class="button new__button">
            <i class="bx bx-cart-alt new__icon"></i>
          </button>
        </SwiperSlide>
        <SwiperSlide class="new__content swiper-slide">
          <div class="new__tag">Novo</div>
          <img src="../../assets/img/new6-img.png" alt="" class="new__img" />
          <h3 class="new__title">Vassoura Voadora</h3>
          <span class="new__subtitle">Acessório</span>

          <div class="new__prices">
            <span class="new__price">R$97.99</span>
            <span class="new__discount">R$149.99</span>
          </div>

          <button class="button new__button">
            <i class="bx bx-cart-alt new__icon"></i>
          </button>
        </SwiperSlide>
      </Swiper>
    </div>
  </section>
</template>
