<template>
  <section class="home container" id="home">
        <div class="swiper home-swiper">
          <div class="swiper-wrapper">
            <!-- HOME SLIDER 1 -->
            <section class="swiper-slide">
              <div class="home__content grid">
                <div class="home__group">
                  <img
                    src="/assets/img/home2-img.png"
                    alt=""
                    class="home__img"
                  />
                  <div class="home__indicator"></div>

                  <div class="home__details-img">
                    <h4 class="home__details-title">Fujiwara Chika</h4>
                    <span class="home__details-subtitle">The Kaguya Tamer</span>
                  </div>
                </div>

                <div class="home__data">
                  <h3 class="home__subtitle">#1 Top Trolling Waifu</h3>
                  <h1 class="home__title">
                    UOOOO <br />
                    Brrrrrr <br />
                    GAOOooo!!
                  </h1>
                  <p class="home__description">
                    Hi, I'm Haydar, people call me "Wilson". I am currently
                    trying to learn something new, Tame my Lovely Girlfriend
                    into anime.
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
            </section>


          </div>
          <div class="swiper-pagination"></div>
        </div>
      </section>

</template>


<script>
export default {
  name: "HeroSection",
}
</script>
<style scoped>
.hero {
  text-align: center;
  padding: 100px 0;
  background: #f5f5f5;
}
</style>
