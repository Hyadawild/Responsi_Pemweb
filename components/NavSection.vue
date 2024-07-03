<template>

    
      <nav class="nav container">
        <a href="#" class="nav__logo">
          <img src="/assets/img/logo.png" alt="" class="nav__logo-img" />
          Weebs
        </a>

        <div class="nav__menu" id="nav-menu">
          <ul class="nav__list">
            <li class="nav__item">
              <a href="#home" class="nav__link active-link">Home</a>
            </li>

            <li class="nav__item">
              <a href="#about" class="nav__link">About</a>
            </li>

            <li class="nav__item">
              <a href="#contact" class="nav__link">Contact</a>
            </li>

            <li class="nav__item">
              <a href="#new" class="nav__link">Project</a>
            </li>

            <a href="#" class="button button--ghost">Follow Me</a>
          </ul>

          <div class="nav__close" id="nav-close">
            <i class="bx bx-x"></i>
          </div>

          <img src="#" alt="" class="nav__img" />
        </div>

        <div class="nav__toggle" id="nav-toggle">
          <i class="bx bx-grid-alt"></i>
        </div>
      </nav>
    

</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
export default {
  name: 'NavSection'
}
</script>
