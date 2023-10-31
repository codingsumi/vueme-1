<template>
  <section class="section testimonials">
    <div class="container">
      <h3 class="text-primary mb-3 text-center">Testimonials</h3>
      <div class="d-flex justify-content-center">
        <swiper
          :slides-per-view="1"
          :space-between="50"
          @swiper="onSwiper"
          @slideChange="onSlideChange"
        >

          <swiper-slide>
              <div class="card border-0 p-3 w-50 mx-auto">
                <div class="card-body text-center">
                  <div class="p-3">
                    <img
                      class="card-img-top rounded-circle p-1 shadows2 w-25 mx-auto d-block"
                      src="@/assets/images/logo.png"
                      alt="Card image"
                    />
                  </div>
                  <p class="card-text fs-14">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione nesciunt
                    beatae omnis officiis. Recusandae voluptatibus totam pariatur quis voluptas
                    quisquam sunt consectetur. Perspiciatis rem velit ab obcaecati corrupti a iusto.
                  </p>
                </div>
                <div class="d-flex gap-1 text-warning fs-14 justify-content-center">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
                <p class="text-muted text-center pb-0 mb-0 mt-1">John Smith</p>
                <small class="text-muted text-center pb-3 fs-13">Web Developer</small>
              </div>
          </swiper-slide>

          <swiper-slide>
              <div class="card border-0 p-3 w-50 mx-auto">
                <div class="card-body text-center">
                  <div class="p-3">
                    <img
                      class="card-img-top rounded-circle p-1 shadows2 w-25 mx-auto d-block"
                      src="@/assets/images/logo.png"
                      alt="Card image"
                    />
                  </div>
                  <p class="card-text fs-14">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione nesciunt
                    beatae omnis officiis. Recusandae voluptatibus totam pariatur quis voluptas
                    quisquam sunt consectetur. Perspiciatis rem velit ab obcaecati corrupti a iusto.
                  </p>
                </div>
                <div class="d-flex gap-1 text-warning fs-14 justify-content-center">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
                <p class="text-muted text-center pb-0 mb-0 mt-1">John Smith</p>
                <small class="text-muted text-center pb-3 fs-13">Web Developer</small>
              </div>
          </swiper-slide>

          <swiper-slide>
              <div class="card border-0 p-3 w-50 mx-auto">
                <div class="card-body text-center">
                  <div class="p-3">
                    <img
                      class="card-img-top rounded-circle p-1 shadows2 w-25 mx-auto d-block"
                      src="@/assets/images/logo.png"
                      alt="Card image"
                    />
                  </div>
                  <p class="card-text fs-14">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione nesciunt
                    beatae omnis officiis. Recusandae voluptatibus totam pariatur quis voluptas
                    quisquam sunt consectetur. Perspiciatis rem velit ab obcaecati corrupti a iusto.
                  </p>
                </div>
                <div class="d-flex gap-1 text-warning fs-14 justify-content-center">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
                <p class="text-muted text-center pb-0 mb-0 mt-1">John Smith</p>
                <small class="text-muted text-center pb-3 fs-13">Web Developer</small>
              </div>
          </swiper-slide>

          <swiper-slide>
              <div class="card border-0 p-3 w-50 mx-auto">
                <div class="card-body text-center">
                  <div class="p-3">
                    <img
                      class="card-img-top rounded-circle p-1 shadows2 w-25 mx-auto d-block"
                      src="@/assets/images/logo.png"
                      alt="Card image"
                    />
                  </div>
                  <p class="card-text fs-14">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione nesciunt
                    beatae omnis officiis. Recusandae voluptatibus totam pariatur quis voluptas
                    quisquam sunt consectetur. Perspiciatis rem velit ab obcaecati corrupti a iusto.
                  </p>
                </div>
                <div class="d-flex gap-1 text-warning fs-14 justify-content-center">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
                <p class="text-muted text-center pb-0 mb-0 mt-1">John Smith</p>
                <small class="text-muted text-center pb-3 fs-13">Web Developer</small>
              </div>
          </swiper-slide>

          <swiper-slide>
              <div class="card border-0 p-3 w-50 mx-auto">
                <div class="card-body text-center">
                  <div class="p-3">
                    <img
                      class="card-img-top rounded-circle p-1 shadows2 w-25 mx-auto d-block"
                      src="@/assets/images/logo.png"
                      alt="Card image"
                    />
                  </div>
                  <p class="card-text fs-14">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione nesciunt
                    beatae omnis officiis. Recusandae voluptatibus totam pariatur quis voluptas
                    quisquam sunt consectetur. Perspiciatis rem velit ab obcaecati corrupti a iusto.
                  </p>
                </div>
                <div class="d-flex gap-1 text-warning fs-14 justify-content-center">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
                <p class="text-muted text-center pb-0 mb-0 mt-1">John Smith</p>
                <small class="text-muted text-center pb-3 fs-13">Web Developer</small>
              </div>
          </swiper-slide>

          <swiper-slide>
              <div class="card border-0 p-3 w-50 mx-auto">
                <div class="card-body text-center">
                  <div class="p-3">
                    <img
                      class="card-img-top rounded-circle p-1 shadows2 w-25 mx-auto d-block"
                      src="@/assets/images/logo.png"
                      alt="Card image"
                    />
                  </div>
                  <p class="card-text fs-14">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione nesciunt
                    beatae omnis officiis. Recusandae voluptatibus totam pariatur quis voluptas
                    quisquam sunt consectetur. Perspiciatis rem velit ab obcaecati corrupti a iusto.
                  </p>
                </div>
                <div class="d-flex gap-1 text-warning fs-14 justify-content-center">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
                <p class="text-muted text-center pb-0 mb-0 mt-1">John Smith</p>
                <small class="text-muted text-center pb-3 fs-13">Web Developer</small>
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
