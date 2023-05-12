<script setup>
import "./styles.scss";
</script>

<template>
  <section class="section footer" id="footer">
    <div class="footer__container container grid">
      <div class="footer__content">
        <a href="#" class="footer__logo">
          <img
            src="../../assets/img/logo.png"
            alt=""
            class="footer__logo-img"
          />
          Halloween
        </a>

        <p class="footer__description">
          Aproveite a noite mais <br />
          assustadora de sua vida.
        </p>

        <div class="footer__social">
          <a
            href="https://www.facebook.com/"
            target="_blank"
            class="footer__social-link"
          >
            <i class="bx bxl-facebook"></i>
          </a>
          <a
            href="https://www.instagram.com/"
            target="_blank"
            class="footer__social-link"
          >
            <i class="bx bxl-instagram-alt"></i>
          </a>
          <a
            href="https://twitter.com/"
            target="_blank"
            class="footer__social-link"
          >
            <i class="bx bxl-twitter"></i>
          </a>
        </div>
      </div>

      <div class="footer__content">
        <h3 class="footer__title">Sobre</h3>

        <ul class="footer__links">
          <li>
            <a href="#" class="footer__link">Sobre nós</a>
          </li>
          <li>
            <a href="#historia" class="footer__link">História</a>
          </li>
          <li>
            <a href="#novidades" class="footer__link">Novidades</a>
          </li>
        </ul>
      </div>

      <div class="footer__content">
        <h3 class="footer__title">Nossos Serviços</h3>

        <ul class="footer__links">
          <li>
            <a href="#doces" class="footer__link">Preços</a>
          </li>
          <li>
            <a href="#desconto" class="footer__link">Descontos</a>
          </li>
          <li>
            <a href="#newsletter" class="footer__link">Entrega</a>
          </li>
        </ul>
      </div>

      <div class="footer__content">
        <h3 class="footer__title">Nossa Empresa</h3>

        <ul class="footer__links">
          <li>
            <a href="#" class="footer__link">Blog</a>
          </li>
          <li>
            <a href="#" class="footer__link">Sobre nós</a>
          </li>
          <li>
            <a href="#" class="footer__link">Nossa missão</a>
          </li>
        </ul>
      </div>
    </div>

    <span class="footer__copy">&#169; MFGF. All rigths reserved</span>

    <img
      src="../../assets/img/footer1-img.png"
      alt=""
      class="footer__img-one"
    />
    <img
      src="../../assets/img/footer2-img.png"
      alt=""
      class="footer__img-two"
    />
  </section>
</template>
