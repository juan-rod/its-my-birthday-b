<template>
  <div class="home">
    <!-- <bday-logo class="front"></bday-logo>
    <bday-logo class="back"></bday-logo> -->
    <page-one/>
    <page-two/>
    <page-three/>
  </div>
</template>

<script>
// @ is an alias to /src
// import BdayLogo from '@/components/BdayLogo.vue'
import PageOne from '@/components/PageOne.vue'
import PageTwo from '@/components/PageTwo.vue'
import PageThree from '@/components/PageThree.vue'
export default {
  name: 'Home',
  components: {
    // BdayLogo,
    PageOne,
    PageTwo,
    PageThree
  }
}
</script>
