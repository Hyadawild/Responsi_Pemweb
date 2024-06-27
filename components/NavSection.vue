<template>

    
      <nav class="nav container">
        <a href="#" class="nav__logo">
          <img src="#" alt="" class="nav__logo-img" />
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
              <a href="#trick" class="nav__link">Waifu</a>
            </li>

            <li class="nav__item">
              <a href="#new" class="nav__link">New Waifu</a>
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
export default {
  name: 'NavSection'
}
</script>
