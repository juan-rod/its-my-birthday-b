<template>
  <div class="page-one">
    <div id="overlay"></div>
    <div class="intro">
      <span>Lets</span>
      <span>hang out!</span>
    </div>
    <div class="img img-1">
      <img src="../assets/video/juan2.gif" alt="">
    </div>
    <div class="img img-2">
      <img src="../assets/video/juan3.gif" alt="">
    </div>
    <div class="img img-3">
      <img src="../assets/video/juan4.gif" alt="">
    </div>
    <div class="img img-4">
      <img src="../assets/video/juan5.gif" alt="">
    </div>
    <!-- <div class="img img-5">
      <img src="../assets/video/juan1.gif" alt="">
    </div> -->
    <date-marquee />
  </div>
</template>

<script>
import DateMarquee from '@/components/DateMarquee.vue'
export default {
  name: 'page-one',
  components: {
    DateMarquee
  }
}
</script>

<style>

</style>