<template>
  <transition name="fadeIn" appear>
    <section id="tools" class="tools col-12">
      <h1 class="tools-title">
        {{ $store.state.lang === 'pt-BR' ? 'Minhas Ferramentas' : 'My Tools' }}
      </h1>

      <div class="container">
        <div class="row">
          <Swiper
            :modules="modules"
            :slides-per-view="3"
            :loop="true"
            :pagination="true"
            :navigation="true"
            :autoplay="true"
            :breakpoints="breakpoints"
          >
            <SwiperSlide>
              <div class="tools-item--wrapper">
                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/sass-icon.png"
                      alt="SASS"
                      width="80px"
                      height="80px"
                      title="SASS"
                    />
                  </div>
                  <h2 class="tools-desc">SASS</h2>
                </div>

                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/jquery-icon.png"
                      alt="jQuery"
                      width="80px"
                      height="80px"
                      title="jQuery"
                    />
                  </div>
                  <h2 class="tools-desc">jQuery</h2>
                </div>
              </div>
            </SwiperSlide>

            <SwiperSlide>
              <div class="tools-item--wrapper">
                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/javascript-icon.png"
                      alt="Javascript"
                      width="80px"
                      height="80px"
                      title="Javascript"
                    />
                  </div>
                  <h2 class="tools-desc">Javascript</h2>
                </div>

                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/vuejs-icon.png"
                      alt="Vue.js"
                      width="80px"
                      height="80px"
                      title="Vue.js"
                    />
                  </div>
                  <h2 class="tools-desc">Vue.js</h2>
                </div>
              </div>
            </SwiperSlide>

            <SwiperSlide>
              <div class="tools-item--wrapper">
                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/vuex-icon.png"
                      alt="Vuex"
                      width="80px"
                      height="80px"
                      title="Vuex"
                    />
                  </div>
                  <h2 class="tools-desc">Vuex</h2>
                </div>

                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/reactjs-icon.png"
                      alt="React.js"
                      width="80px"
                      height="80px"
                      title="React.js"
                    />
                  </div>
                  <h2 class="tools-desc">React.js</h2>
                </div>
              </div>
            </SwiperSlide>

            <SwiperSlide>
              <div class="tools-item--wrapper">
                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/styled-components-icon.svg"
                      alt="Styled Components"
                      width="80px"
                      height="80px"
                      title="Styled Components"
                    />
                  </div>
                  <h2 class="tools-desc">Styled Components</h2>
                </div>

                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/bootstrap.png"
                      alt="Bootstrap"
                      width="80px"
                      height="80px"
                      title="Bootstrap"
                    />
                  </div>
                  <h2 class="tools-desc">Bootstrap</h2>
                </div>
              </div>
            </SwiperSlide>

            <SwiperSlide>
              <div class="tools-item--wrapper">
                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/foundation-icon.png"
                      alt="Foundation"
                      width="80px"
                      height="80px"
                      title="Foundation"
                    />
                  </div>
                  <h2 class="tools-desc">Foundation</h2>
                </div>

                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/tailwind-icon.png"
                      alt="Tailwind CSS"
                      width="80px"
                      height="80px"
                      title="Tailwind CSS"
                    />
                  </div>
                  <h2 class="tools-desc">Tailwind CSS</h2>
                </div>
              </div>
            </SwiperSlide>

            <SwiperSlide>
              <div class="tools-item--wrapper">
                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/vite-icon.png"
                      alt="Vite"
                      width="80px"
                      height="80px"
                      title="Vite"
                    />
                  </div>
                  <h2 class="tools-desc">Vite</h2>
                </div>

                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/nodejs-icon.png"
                      alt="NodeJs"
                      width="80px"
                      height="80px"
                      title="NodeJs"
                    />
                  </div>
                  <h2 class="tools-desc">NodeJs</h2>
                </div>
              </div>
            </SwiperSlide>

            <SwiperSlide>
              <div class="tools-item--wrapper">
                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/mongodb-icon.png"
                      alt="MongoDB"
                      width="80px"
                      height="80px"
                      title="MongoDB"
                    />
                  </div>
                  <h2 class="tools-desc">MongoDB</h2>
                </div>

                <div class="tools-item col-6 col-md-4">
                  <div class="tools-img">
                    <img
                      src="@/assets/img/github.png"
                      alt="Github"
                      width="80px"
                      height="80px"
                      title="Github"
                    />
                  </div>
                  <h2 class="tools-desc">Github</h2>
                </div>
              </div>
            </SwiperSlide>
          </Swiper>
        </div>
      </div>
    </section>
  </transition>
</template>

<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Pagination, Navigation } from 'swiper/modules';
import applySEO from '@/globals/applySEO.js';
import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';

export default {
  data() {
    return {
      modules: [Pagination, Navigation],
      breakpoints: {
        800: {
          slidesPerView: 3,
        },
        500: {
          slidesPerView: 2,
        },
        320: {
          slidesPerView: 1,
        },
      },
    };
  },
  components: {
    Swiper,
    SwiperSlide,
  },
  computed: {
    currentLang() {
      return this.$store.state.lang;
    },
  },
  watch: {
    currentLang(newLang) {
      if (newLang === 'pt-BR') {
        applySEO({
          title: 'Stack',
          description: 'Um pouco sobre minha stack de conhecimentos.',
        });
      } else {
        applySEO({
          title: 'Stack',
          description: 'A little bit about my knowledge stack.',
        });
      }
    },
  },
  mounted() {
    if (this.$store.state.lang === 'pt-BR') {
      applySEO({
        title: 'Stack',
        description: 'Um pouco sobre minha stack de conhecimentos.',
      });
    } else {
      applySEO({
        title: 'Stack',
        description: 'A little bit about my knowledge stack.',
      });
    }
  },
};
</script>

<style scoped lang="scss">
.tools {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-flow: column;
  width: 100%;
  max-width: 800px;
  height: auto;
  margin: 0 auto;
  margin-top: 20px;
  padding-top: 40px;
  border-radius: 15px;
  box-shadow: 3px 5px 10px #212121;
  transition: all 0.5s ease;

  .tools {
    &-title {
      font-family: $sulphur;
      font-size: 24px;
      line-height: 24px;
      font-weight: 700;
      color: $color-main;
      display: flex;
      align-items: center;
      justify-content: center;
      text-transform: uppercase;
      margin-bottom: 20px;
      letter-spacing: 0.5px;
      transition: all 0.5s ease;
    }

    &-item {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      flex-flow: column;

      &--wrapper {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-flow: column;
      }
    }

    &-img {
      width: 100%;
      max-width: 100px;
      height: auto;
      max-height: 100px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 10px;

      img {
        width: 80px;
        height: auto;
      }
    }

    &-desc {
      font-family: $sulphur;
      font-size: 24px;
      line-height: 24px;
      font-weight: 700;
      color: $color-main;
      display: flex;
      align-items: center;
      justify-content: center;
      text-transform: uppercase;
      text-align: center;
      margin-bottom: 20px;
      letter-spacing: 0.5px;
    }
  }
}

@media (max-width: 800px) {
  .tools {
    width: calc(100% - 30px);
  }
}
</style>
