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
  <section class="home" id="home">
    <Swiper
      loop
      mousewheel
      :modules="modules"
      :pagination="{ clickable: true }"
      :autoplay="{
        delay: 6000,
        disableOnInteraction: false,
      }"
      class="swiper home-swiper"
    >
      <SwiperSlide>
        <div class="home__content grid">
          <div class="home__group">
            <img
              src="../../assets/img/home1-img.png"
              alt=""
              class="home__img"
            />
            <div class="home__indicator"></div>

            <div class="home__details-img">
              <h4 class="home__details-title">Kinzo</h4>
              <span class="home__details-subtitle">A abóbora viva</span>
            </div>
          </div>

          <div class="home__data">
            <h3 class="home__subtitle">#1 Top Fantasmas mais assutadores</h3>
            <h1 class="home__title">
              UOOOO <br />
              DOCES OU <br />
              TRAVESSURAS!!
            </h1>
            <p class="home__description">
              Olá sou uma abóbora, mas as pessoas me chamam de "Kinzo".
              Atualmente, estou tentando aprender algo novo, quero ser
              compositor, mas ainda preciso aprender como tocar violão sem ter
              braços.
            </p>

            <div class="home__buttons">
              <a href="#" class="button">Compre Agora</a>
              <a href="#" class="button--link button--flex"
                >História <i class="bx bx-right-arrow-alt button__icon"></i
              ></a>
            </div>
          </div>
        </div>
      </SwiperSlide>
      <SwiperSlide>
        <div class="home__content grid">
          <div class="home__group">
            <img
              src="../../assets/img/home2-img.png"
              alt=""
              class="home__img"
            />
            <div class="home__indicator"></div>

            <div class="home__details-img">
              <h4 class="home__details-title">Jabbi & Olga</h4>
              <span class="home__details-subtitle"
                >Nenhuma palavra pode descrevê-los</span
              >
            </div>
          </div>

          <div class="home__data">
            <h3 class="home__subtitle">#2 Top Melhor Dupla</h3>
            <h1 class="home__title">
              DEVOLVA <br />
              MINHA TORTA DE <br />
              CHOCOLATE
            </h1>
            <p class="home__description">
              Jabbi rouba a torta da irmã e come tudo em uma mordida, uma fera
              faminta. Olga não consegue mais esconde a raiva de Jabbi.
            </p>

            <div class="home__buttons">
              <a href="#" class="button">Compre Agora</a>
              <a href="#" class="button--link button--flex"
                >História <i class="bx bx-right-arrow-alt button__icon"></i
              ></a>
            </div>
          </div>
        </div>
      </SwiperSlide>
      <SwiperSlide>
        <div class="home__content grid">
          <div class="home__group">
            <img
              src="../../assets/img/home3-img.png"
              alt=""
              class="home__img"
            />
            <div class="home__indicator"></div>

            <div class="home__details-img">
              <h4 class="home__details-title">Rei Boro</h4>
              <span class="home__details-subtitle">Fantasma Veterano</span>
            </div>
          </div>

          <div class="home__data">
            <h3 class="home__subtitle">#3 Top Fantasmas mais assutadores</h3>
            <h1 class="home__title">
              RETORNO<br />
              DA CAVEIRA <br />
              FLAMEJANTE
            </h1>
            <p class="home__description">
              Em busca de seu cachorrinho, o Rei Boro voltou de sua trágica
              morte. Com seu poder certificado por Hogwarts, ele promete ser um
              herói para todos os fantasmas.
            </p>

            <div class="home__buttons">
              <a href="#" class="button">Compre Agora</a>
              <a href="#" class="button--link button--flex"
                >História <i class="bx bx-right-arrow-alt button__icon"></i
              ></a>
            </div>
          </div>
        </div>
      </SwiperSlide>
    </Swiper>
  </section>
</template>
