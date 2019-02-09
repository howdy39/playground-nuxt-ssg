<template>
  <!-- You can find this swiper instance object in current component by the "mySwiper"  -->
  <div>
    すまん動かない。。
    <div v-swiper="swiperOption" class="my-swiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <img src="/subdirectory/puppy1.jpeg">
        </div>
        <div class="swiper-slide">
          <img src="/subdirectory/puppy2.jpeg">
        </div>
        <div class="swiper-slide">
          <img src="/subdirectory/puppy3.jpeg">
        </div>
      </div>
    </div>
    {{ swiperOption }}
  </div>
</template>

<script>
/* eslint-disable no-console */

export default {
  data() {
    return {
      swiperOption: {
        spaceBetween: 0,
        effect: 'fade',
        speed: 2800,
        loop: true,
        centeredSlides: true,
        autoplay: {
          delay: 5000,
          disableOnInteraction: false
        }
      }
    }
  },
  mounted() {}
}
</script>


<style lang="css" scoped>
.my-swiper {
  height: 300px;
  width: 100%;
}
.swiper-slide {
  text-align: center;
  font-size: 38px;
  font-weight: 700;
  background-color: #eee;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
