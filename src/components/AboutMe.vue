<template>
  <main class="main">
    <section class="about about-me" id="aboutMeSection">
      <div class="container about__content">
        <h2 class="about__title">Обо мне</h2>
        <p class="about__descr">
          Здравствуйте, меня зовут Бекзод и я Front-End разработчик. Я использую самые свежие и востребованные
          технологии чтобы в будущем не было проблем с поддержкой сайта и оно было всегда актуальным
        </p>
        <div class="about__cards">
          <div class="about__card">
            <img src="../assets/Group 14.svg" alt="" />
            <h3 class="about__card-title">Полное имя</h3>
            <p class="about__card-descr">Султонмуродов Бекзод Джамшидович</p>
          </div>
          <div class="about__card">
            <img src="../assets/Group 14.svg" alt="" />
            <h3 class="about__card-title">Эл. почта</h3>
            <p class="about__card-descr">hilinkiy@gmail.com</p>
          </div>
          <div class="about__card">
            <img src="../assets/Group 14.svg" alt="" />
            <h3 class="about__card-title">Telegram</h3>
            <p class="about__card-descr">@hilinkiy</p>
          </div>
          <div class="about__card">
            <img src="../assets/Group 14.svg" alt="" />
            <h3 class="about__card-title">Номер телефона</h3>
            <p class="about__card-descr">+998 (99) 180-55-65</p>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script setup>
import { defineComponent, ref } from 'vue'

const aboutMeSection = ref(null);

</script>

<style>
@media (max-width: 920.99px) {
  .about__cards {
    flex-wrap: wrap;
    justify-content: center;
    gap: 40px;
  }
}

@media (max-width: 690.99px) {
  .about__descr {
    width: 70%;
  }
}
</style>