<template>
  <div class="wrapper">
    <div class="header-section">
      <Nav />
      <Hero />
    </div>
    <RentSection/>
  </div>
</template>
<script>


import Nav from '@/components/Nav.vue'
import Hero from '@/components/Hero.vue'
import RentSection from '@/components/rentPage.vue'

export default {
  name: 'Home',
  components: {Nav, Hero,RentSection}
}
</script>

<style lang="scss">

</style>
