<template>
  <main class="main">
    <section class="projects" id='projects'>
      <div class="container projects__content">
        <h5 class="projects__title">Некоторые из моих проектов</h5>
        <h6 class="projects__block-title">VUE-cinema:</h6>
        <div class="projects__block">
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_1.png" alt="" class="img" />
          </div>
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_2.png" alt="" class="img" />
          </div>
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_3.png" alt="" class="img" />
          </div>
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_4.png" alt="" class="img" />
          </div>
        </div>
        <h6 class="projects__block-title">BMW:</h6>
        <div class="projects__block">
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_5.png" alt="" class="img" />
          </div>
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_6.png" alt="" class="img" />
          </div>
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_7.png" alt="" class="img" />
          </div>
        </div>
        <h6 class="projects__block-title">ZONE:</h6>
        <div class="projects__block">
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_8.png" alt="" class="img" />
          </div>
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_9.png" alt="" class="img" />
          </div>
          <div class="projects__block-img">
            <img src="../assets/img/Screenshot_10.png" alt="" class="img" />
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script setup>
</script>

<style>
@media (max-width: 950.99px) {
  .projects__block-img {
    width: 500px;
    height: 300px;
    position: relative;
  }

  .img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
}
</style>