<script setup>
import "./styles.scss";
</script>

<template>
  <header class="header" id="header">
    <nav class="nav container">
      <a href="#" class="nav__logo">
        <img src="../../assets/img/logo.png" alt="" class="nav__logo-img" />
        Halloween
      </a>

      <div class="nav__menu" id="nav-menu">
        <ul class="nav__list">
          <li class="nav__item">
            <a href="#home" class="nav__link active-link">Home</a>
          </li>

          <li class="nav__item">
            <a href="#historia" class="nav__link">História</a>
          </li>

          <li class="nav__item">
            <a href="#doces" class="nav__link">Doces</a>
          </li>

          <li class="nav__item">
            <a href="#novidades" class="nav__link">Novidades</a>
          </li>

          <a
            href="https://www.linkedin.com/in/mauricio-guimar%C3%A3es-5312a41a6/"
            target="__blank"
            class="button button--ghost"
            >Contato</a
          >
        </ul>

        <div class="nav__close" id="nav-close">
          <i class="bx bx-x"></i>
        </div>

        <img src="../../assets/img/nav-img.png" alt="" class="nav__img" />
      </div>

      <div class="nav__toggle" id="nav-toggle">
        <i class="bx bx-grid-alt"></i>
      </div>
    </nav>
  </header>
</template>

<style lang="scss"></style>
