<template>
  <header class="header">
    <nav class="nav">
      <div class="container nav__content">
        <p class="nav__logo">PORTFOLIO</p>
        <ul class="nav__list">
          <li>
            <a href="#" class="nav__list-link" @click="scrollTo(aboutMe)">
              About me
            </a>
          </li>
          <li>
            <a href="#" class="nav__list-link" @click="scrollTo(Job)">
              Services
            </a>
          </li>
          <li>
            <a href="#" class="nav__list-link" @click="scrollTo(projects)">
              Projects
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script setup>
import { defineProps } from 'vue'

const props = defineProps(['scrollToSection'])

const scrollTo = (sectionRef) => {
  props.scrollToSection(sectionRef)
}
</script>

<style>
@media (max-width: 630.99px) {
  .nav__content {
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }
}

@media (max-width: 340.99px) {
  .nav__list {
    flex-wrap: wrap;
    justify-content: center;
  }
}
</style>