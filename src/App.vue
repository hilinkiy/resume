<template>
  <div class="wrapper">
    <header class="header">
      <nav class="nav">
        <div class="container nav__content">
          <p class="nav__logo">PORTFOLIO</p>
          <ul class="nav__list">
            <li>
              <a href="#" class="nav__list-link" @click='scroll'>
                Обо мне
              </a>
            </li>
            <li>
              <a href="#" class="nav__list-link" @click="scroll2">
                Услуги и стэк технологий
              </a>
            </li>
            <li>
              <a href="#" class="nav__list-link" @click="scroll3">
                Проекты
              </a>
            </li>
            <li>
              <a href="#" class="nav__list-link" @click="scroll4">
                Соц.сети
              </a>
            </li>
          </ul>
        </div>
      </nav>
    </header>
    <HeaderContent />
    <AboutMe ref="aboutMe" />
    <Job ref="job" />
    <Skills ref="skills" />
    <Projects ref="projects" />
    <Footer />
  </div>
</template>

<script setup>
import HeaderContent from "./components/HeaderContent.vue"
import AboutMe from "./components/AboutMe.vue"
import Job from "./components/Job.vue"
import Skills from "./components/Skills.vue"
import Projects from "./components/Projects.vue"
import Footer from "./components/Footer.vue"

const scroll = () => {
  const element = document.getElementById('aboutMeSection')
  element.scrollIntoView({ behavior: 'smooth' })
}
const scroll2 = () => {
  const element = document.getElementById('job')
  element.scrollIntoView({ behavior: 'smooth' })
}
const scroll3 = () => {
  const element = document.getElementById('projects')
  element.scrollIntoView({ behavior: 'smooth' })
}
const scroll4 = () => {
  const element = document.getElementById('societies')
  element.scrollIntoView({ behavior: 'smooth' })
}
</script>
