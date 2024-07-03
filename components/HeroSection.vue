<template>
  <div class="hero">
  <section class="home container" id="home">
    <div class="swiper home-swiper">
      <div class="swiper-wrapper">
        <!-- HOME SLIDER 1 -->
        <div class="swiper-slide">
          <div class="home__content grid">
            <div class="home__group">
              <img src="/assets/img/miyuki.png" alt="" class="home__img" />
              <div class="home__indicator"></div>
              <div class="home__details-img">
                <h4 class="home__details-title">Shiba Miyuki</h4>
                <span class="home__details-subtitle">The Irregular Mage</span>
              </div>
            </div>
            <div class="home__data">
              <h3 class="home__subtitle">#1 Top Soft Waifu</h3>
              <h1 class="home__title">
                UOOOO <br />
                Brrrrrr <br />
                GAOOooo!!
              </h1>
              <p class="home__description">
                Hi, I'm Haydar, people call me "Wilson". I am currently trying
                to learn something new, Tame my Lovely Girlfriend into anime.
              </p>
              <div class="home__buttons">
                <a
                  href="https://www.youtube.com/watch?v=awBszQL1U50"
                  target="_blank"
                  class="button"
                  >Lick Now</a
                >
                <a
                  href="https://mywaifulist.moe/waifu/chika-fujiwara-kaguya-sama-love-is-war"
                  target="_blank"
                  class="button--link button--flex"
                  >Track Record
                  <i class="bx bx-right-arrow-alt button__icon"></i
                ></a>
              </div>
            </div>
          </div>
        </div>

        <!-- HOME SLIDER 2 -->
        <div class="swiper-slide">
          <div class="home__content grid">
            <div class="home__group">
              <img src="assets/img/home2-img.png" alt="" class="home__img" />
              <div class="home__indicator"></div>
              <div class="home__details-img">
                <h4 class="home__details-title">Kamsito Ayaka "Chibi Ayayo"</h4>
                <span class="home__details-subtitle">No words can describe them sibling</span>
              </div>
            </div>
            <div class="home__data">
              <h3 class="home__subtitle">#2 top Best Soft Fuwa-Fuwa Waifu</h3>
              <h1 class="home__title">
                BRING BACK <br />
                MY ONIII-CHANN <br />
                MAAAaaaa
              </h1>
              <p class="home__description">
                Yoimiya steals Ayayo from his sister and lick them all in her
                room, a leaks beast. Ayaka can no longer contain his anger
                towards Ayayo.
              </p>
              <div class="home__buttons">
                <a href="#" target="_blank" class="button">Lick Now</a>
                <a href="#" target="_blank" class="button--link button--flex"
                  >Track Record
                  <i class="bx bx-right-arrow-alt button__icon"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
  </section>
</div>
</template>

<script>
import { onMounted } from 'vue';
import { Swiper } from 'swiper';

export default {
  name: "HeroSection",
  setup() {
    onMounted(() => {
      new Swiper(".home-swiper", {
        slidesPerView: 1,
        spaceBetween: 0,
        loop: true,
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev",
        },
        autoplay: {
          delay: 100,
          disableOnInteraction: false,
        },
        pagination: {
          el: '.swiper-pagination',
          clickable: true,
        },
      });
    });
  },
}
</script>

<style scoped>
.hero {
  text-align: center;
  padding: 100px 0;
  background: transparent ;
}
</style>
