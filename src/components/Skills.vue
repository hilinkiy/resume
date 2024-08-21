<template>
  <main class="main">
    <section class="skills">
      <div class="container skills__content">
        <h4 class="skills__title">Стэк технологий</h4>
        <div class="skills__table">
          <div class="skills__table-skill">
            <p class="skill__name">
              HTML, CSS <br/> JS, TS
            </p>
          </div>
          <div class='border'></div>
          <div class="skills__table-skill">
            <p class="skill__name">Vue.js, Nuxt.js</p>
          </div>
          <div class='border'></div>
          <div class="skills__table-skill">
            <p class="skill__name">React.js, Next.js</p>
          </div>
          <div class='border'></div>
          <div class="skills__table-skill">
            <p class="skill__name">Nest.js</p>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {}
</script>

<style scoped>
.border {
  background: rgba(255, 255, 255, .4);
  width: 2px;
  height: 100px;
}

@media (max-width: 980.99px) {
  .skills__table {
    flex-wrap: wrap;
    justify-content: center;
    gap: 40px;
    padding: 20px;
  }
}
</style>