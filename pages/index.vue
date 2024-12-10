<script setup lang="ts"></script>
<template>
  <section>
    <div class="hero-content position-relative">
      <NuxtImg
        src="/img/body/hero.webp"
        alt="Biztos Alkuszom"
        class="hero-content__img"
        height="100%"
      />

      <div class="hero-content__tBox position-absolute bg-color-w">
        <h1 class="hero-content__tBox__h1 text-transform-uppercase">
          Profi csapat, gördülékeny ügyintézés, garantált nyugalom.
        </h1>
        <p class="hero-content__tBox__p">
          Legyen szó előzetes átvizsgálásról, felkészítésről vagy ügyintézésről,
          mi leveszünk minden terhet a válladról. Te hozd az autót, mi hozzuk a
          megoldást!
        </p>
        <NuxtLink to="/" class="hero-content__tBox__link page-link text-color-w"
          >Ajánlatkérés</NuxtLink
        >
      </div>
    </div>
  </section>
</template>
