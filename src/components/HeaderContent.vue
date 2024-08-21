<template>
  <header class="header">
    <div class="container header__content">
      <div class="header__text">
        <h1 class="header__title">Bekhzod Sultonmurodov</h1>
        <p class="header__descr">
          Front-End разработчик 
          <br />
          Место учебы: Proweb.
          <br />
          Учеба была успешно окончена на диплом
        </p>
      </div>
    </div>
  </header>
</template>

<script setup>
</script>

<style>
@media (max-width: 1100.99px) {
  .header__content {
    flex-direction: column-reverse;
    gap: 20px;
    align-items: center;
  }

  .header__title {
    text-align: center;
  }

  .header__descr {
    text-align: center;
  }
}

@media (max-width: 630.99px) {
  .header__img {
    width: 80%;
  }

  .header__title {
    width: 100%;
  }

  .header__descr {
    width: 100%;
  }

  .header__content {
    justify-content: center;
  }
}

@media (max-width: 400.99px) {
  .header__title {
    font-size: 35px;
  }

  .nav__list {
    gap: 20px;
  }

  .header__img {
    width: 95%;
  }
}
</style>