<template>
  <section class="section bg-1">
    <div class="container">
      <h1 class="text-primary display-6 text-center mb-5">Our Portfolio</h1>
      <div class="d-flex">
        <swiper
          :slides-per-view="4"
          :space-between="20"
          @swiper="onSwiper"
          @slideChange="onSlideChange"
        >
          <swiper-slide>
            <div class="card shadows1 border-0">
              <div class="card-body p-0">
                <div class="port-img">
                    <img src="@/assets/images/bot.webp" class="img-fluid rounded-top" alt="portfolio image" />
                </div>
                <div class="d-flex justify-content-between p-3 pb-0">
                    <p>Bootstrap 5</p>
                    <a href="#" class="text-success">Read More</a>
                </div>

              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="card shadows3 border-0">
              <div class="card-body p-0">
                <div class="port-img">
                    <img src="@/assets/images/bot.webp" class="img-fluid rounded-top" alt="portfolio image" />
                </div>
                <div class="d-flex justify-content-between p-3 pb-0">
                    <p>Bootstrap 5</p>
                    <a href="#" class="text-success">Read More</a>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="card shadows3 border-0">
              <div class="card-body p-0">
                <div class="port-img">
                    <img src="@/assets/images/bot.webp" class="img-fluid rounded-top" alt="portfolio image" />
                </div>
                <div class="d-flex justify-content-between p-3 pb-0">
                    <p>Bootstrap 5</p>
                    <a href="#" class="text-success">Read More</a>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="card shadows3 border-0">
              <div class="card-body p-0">
                <div class="port-img">
                    <img src="@/assets/images/bot.webp" class="img-fluid rounded-top" alt="portfolio image" />
                </div>
                <div class="d-flex justify-content-between p-3 pb-0">
                    <p>Bootstrap 5</p>
                    <a href="#" class="text-success">Read More</a>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="card shadows3 border-0">
              <div class="card-body p-0">
                <div class="port-img">
                    <img src="@/assets/images/bot.webp" class="img-fluid rounded-top" alt="portfolio image" />
                </div>
                <div class="d-flex justify-content-between p-3 pb-0">
                    <p>Bootstrap 5</p>
                    <a href="#" class="text-success">Read More</a>
                </div>
              </div>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div class="card shadows3 border-0">
              <div class="card-body p-0">
                <div class="port-img">
                    <img src="@/assets/images/bot.webp" class="img-fluid rounded-top" alt="portfolio image" />
                </div>
                <div class="d-flex justify-content-between p-3 pb-0">
                    <p>Bootstrap 5</p>
                    <a href="#" class="text-success">Read More</a>
                </div>
              </div>
            </div>
          </swiper-slide>
        </swiper>
      </div>
    </div>
  </section>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue'

// Import Swiper styles
import 'swiper/css'

export default {
  components: {
    Swiper,
    SwiperSlide
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper)
    }
    const onSlideChange = () => {
      console.log('slide change')
    }
    return {
      onSwiper,
      onSlideChange
    }
  }
}
</script>
