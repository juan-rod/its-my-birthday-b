<template>
  <div class="page-two">
     <!-- <div id="block"></div> -->
    <div class="bday-logo-wrapper">
      <bday-logo class="front"></bday-logo>
      <bday-logo class="back"></bday-logo>
    </div>
    <div id="overlay"></div>
    <date-marquee />
  </div>
</template>

<script>
import BdayLogo from '@/components/BdayLogo.vue'
import DateMarquee from '@/components/DateMarquee.vue'
export default {
  name: 'page-two',
  components: {
    DateMarquee,
    BdayLogo
  }
}
</script>

<style>

</style>