<template>
  <main class="main">
    <section class="job" id='job'>
      <div class="container job__content">
        <h3 class="job__title">Мои услуги</h3>
        <div class="job__cards" @click="scrollToBottom">
          <div class="job__card">
            <img src="../assets/soft.png" alt="" />
            <p class="job__card-descr">Разработка веб приложений</p>
          </div>
          <div class="job__card">
            <img src="../assets/dev.png" alt="" />
            <p class="job__card-descr">Разработка веб сайтов</p>
          </div>
          <div class="job__card">
            <img src="../assets/design.png" alt="" />
            <p class="job__card-descr webdes">Веб дизайн</p>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script setup>
</script>

<style scoped>
.job__card:hover .job__card-descr {
  color: white;
}

@media (max-width: 1100.99px) {
  .job__cards {
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }
}

@media (max-width: 360.99px) {
  .job__card {
    width: 280px;
    padding: 20px;
  }
}
</style>