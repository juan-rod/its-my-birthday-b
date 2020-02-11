<template>
  <div class="page-three">
    <!-- <div class="img img-5">
      <img src="../assets/video/juan1.gif" alt="">
    </div> -->
    <div class="a-note">
      <p>last minute.</p>
      <p>i know.</p>
      <p>bday came out of no where.</p>
      <p>this is come and go.</p>
      <p>call me, beep me </p>
      <p>if you wanna reach me.</p>
    </div>
    <div class="place">
      <div class="restaurant">
        <p>TAKOBA</p>
        <p>TAKOBA</p>
        <p>TAKOBA</p>
        <p>TAKOBA</p>
      </div>
      <p class="time">1:30pm</p>
      <p class="time">til</p>
      <p class="blackout blackout-1">blackout</p>
      <p class="blackout blackout-2">blackout</p>
      <p class="blackout blackout-3">blackout</p>
      <p class="blackout blackout-4">blackout</p>

    </div>
    <date-marquee />
  </div>
</template>

<script>
import DateMarquee from '@/components/DateMarquee.vue'
export default {
  name: 'page-three',
  components: {
    DateMarquee
  }
}
</script>

<style>

</style>