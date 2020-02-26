<template>
  <div class="home">
    <post-date />
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
import PostDate from '@/components/PostDate.vue'
export default {
  name: 'Home',
  components: {
    PageOne,
    PageTwo,
    PageThree,
    PostDate
  }
}
</script>
