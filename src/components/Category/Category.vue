<script setup>
import "./styles.scss";
</script>

<template>
  <section class="section category" id="categoria">
    <h2 class="section__title">
      Categoria de<br />
      Sustos Favoritos
    </h2>

    <div class="category__container container grid">
      <div class="category__data">
        <img
          src="../../assets/img/category1-img.png"
          alt=""
          class="category__img"
        />
        <h3 class="category__title">Fantasmas</h3>
        <p class="category__description">
          Escolha os fantasmas mais assustadores.
        </p>
      </div>

      <div class="category__data">
        <img
          src="../../assets/img/category2-img.png"
          alt=""
          class="category__img"
        />
        <h3 class="category__title">Abóboras</h3>
        <p class="category__description">
          Temos as abóboras mais assutadoras que existem.
        </p>
      </div>

      <div class="category__data">
        <img
          src="../../assets/img/category3-img.png"
          alt=""
          class="category__img"
        />
        <h3 class="category__title">Chapéu de Bruxa</h3>
        <p class="category__description">
          Escolha os chapéus de bruxa mais estilosos que existem.
        </p>
      </div>
    </div>
  </section>
</template>
