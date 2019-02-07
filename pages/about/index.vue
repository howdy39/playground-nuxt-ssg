<template>
  <div>
    <h1>
      about page
    </h1>
    <MySwiper />
    <nuxt-link to="/">
      Top
    </nuxt-link>
  </div>
</template>

<script>
import MySwiper from '~/components/MySwiper'
export default {
  components: { MySwiper }
}
</script>

<style>
</style>
