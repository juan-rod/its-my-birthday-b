<template>
  <div class="home">
    <bday-logo></bday-logo>
    <arrow-left/>
    <arrow-down/>
    <arrow-up/>
    <arrow-right/>
  </div>
</template>

<script>
// @ is an alias to /src
import BdayLogo from '@/components/BdayLogo.vue'
import ArrowLeft from '@/components/ArrowLeft.vue'
import ArrowDown from '@/components/ArrowDown.vue'
import ArrowUp from '@/components/ArrowUp.vue'
import ArrowRight from '@/components/ArrowRight.vue'
// import InvitePage from '@/components/Invite.vue'
export default {
  name: 'Home',
  components: {
    BdayLogo,
    ArrowLeft,
    ArrowDown,
    ArrowUp,
    ArrowRight
    // InvitePage
  }
}
</script>
