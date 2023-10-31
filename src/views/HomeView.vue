<script setup>
import TestimonialView  from '../components/TestimonialView.vue'
import PortfolioView  from '../components/PortfolioView.vue'
</script>
<template>
  <section>
    <swiper
      class="hero-section"
      :modules="modules"
      :slides-per-view="1"
      :space-between="0"
      navigation
      :pagination="{ clickable: true }"
      :scrollbar="{ draggable: true }"
      :autoplay="{ autoplay: true }"
      @swiper="onSwiper"
      @slideChange="onSlideChange"
    >
      <swiper-slide>
        <img src="@/assets/images/slider1.jpg" alt="slider1" class="img-fluid" />
      </swiper-slide>
      <swiper-slide>
        <img src="@/assets/images/slider2.jpg" alt="slider2" class="img-fluid" />
      </swiper-slide>
      <swiper-slide>
        <img src="@/assets/images/slider3.jpg" alt="slider3" class="img-fluid" />
      </swiper-slide>
    </swiper>
  </section>

  <section class="section services" style="background-color: rgb(245, 245, 245)">
    <div class="container">
      <h1 class="display-4 text-center text-primary mb-5">What We Do</h1>
      <div class="row mt-3">
        <div class="col-md-4">
          <div class="card shadows10 border-0">
            <div class="card-body">
              <img src="@/assets/images/services/ecommerce.jpg" alt="" class="img-fluid" />
              <p class="pt-3">
                From creating shopping carts and third-party integrations to the safety and security
                of your E-commerce, we have got you covered.
              </p>
              <h3 class="fw-light text-dark border-top pt-2">E-commerce Solutions</h3>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card shadows10 border-0">
            <div class="card-body">
              <img src="@/assets/images/services/web.jpg" alt="" class="img-fluid" />
              <p class="pt-3">
                From the conceptualisation of website and web application design to completing it,
                we offer all types of web solutions that can take your business to new heights.
              </p>
              <h3 class="fw-light text-dark border-top pt-2">Web Application Solutions</h3>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card shadows10 border-0">
            <div class="card-body">
              <img src="@/assets/images/services/mobile.png" alt="" class="img-fluid" />
              <p class="pt-3">
                Mobile applications are useful in enhancing user experience. We offer solutions for
                mobile applications so you can take your business closer to your clients.
              </p>
              <h3 class="fw-light text-dark border-top pt-2">Mobile Application Solutions</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section container">
    <h1 class="text-success display-5 mb-5">Some Frequently Asked Questions About Our Services</h1>
    <div class="row">
      <div class="col-md-6">
        <div class="accordion shadows1" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button bg-primary text-white shadows1"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
                Do I Need an IT Solutions Team ?
              </button>
            </h2>
            <div
              id="collapseOne"
              class="accordion-collapse collapse show"
              aria-labelledby="headingOne"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                An IT solutions team will help you resolve any and all of your IT-related issues be
                it website development, web designing, app development etc
              </div>
            </div>
          </div>

          <div class="accordion-item">
            <h2 class="accordion-header" id="headingTwo">
              <button
                class="accordion-button collapsed bg-primary text-white shadows1"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
                What are Your Specialities ?
              </button>
            </h2>
            <div
              id="collapseTwo"
              class="accordion-collapse collapse"
              aria-labelledby="headingTwo"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                Our team specialises in multiple programming languages that help them to create some
                of the best custom websites and applications for our clients.
              </div>
            </div>
          </div>

          <div class="accordion-item">
            <h2 class="accordion-header" id="headingThree">
              <button
                class="accordion-button collapsed bg-primary text-white shadows1"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >
                What Industry do You Work for ?
              </button>
            </h2>
            <div
              id="collapseThree"
              class="accordion-collapse collapse"
              aria-labelledby="headingThree"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                We have experience working in all kinds of industries including e-commerce
                industries, hospitality, MSMEs and pharmaceutical industry etc.
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-6">
        <img src="@/assets/images/faq.png" class="img-fluid shadows1 rounded" alt="faq" />
      </div>
    </div>
  </section>

  <section class="section products" style="background-color: rgb(245, 245, 245)">
    <div class="container">
      <h4 class="mb-5">Trending Products</h4>
      <div class="row">

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/1.webp" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/2.webp" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/3.png" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/4.png" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/5.webp" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/6.webp" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/7.webp" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/8.jpg" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/9.png" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/10.jpg" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/11.png" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-2 mb-5">
          <div class="card shadows1 border-0 rounded p-2">
            <div class="card-body p-0">
              <div class="product-img">
                <img src="@/assets/images/products/12.webp" class="img-fluid p-2" alt="product1" />
              </div>
             <div class="desc p-2">
                <h6 class="mb-0">Dragon Earbuds</h6>
                 <div class="d-flex text-default">
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                    <i class="fas fa-star" style="font-size: 10px;"></i>
                </div>
              </div>
            </div>
          </div>
        </div>



      </div>
    </div>
  </section>

  <TestimonialView />
  <PortfolioView />
</template>
<script>
import { Parallax, A11y, Autoplay } from 'swiper/modules'
import { Swiper, SwiperSlide } from 'swiper/vue'
// Import Swiper styles
import 'swiper/css'
import 'swiper/css/autoplay'
import 'swiper/css/parallax'

// Import Swiper styles
export default {
  components: {
    Swiper,
    SwiperSlide,
    TestimonialView,
    PortfolioView
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
      onSlideChange,
      modules: [A11y, Autoplay, Parallax]
    }
  }
}
</script>
