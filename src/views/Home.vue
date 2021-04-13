<template>
  <div class="wrapper">
    <div class="header-section">
      <Nav />
      <Hero />
    </div>
      <PriceSection/>
      <Contacts/>
      <Footer/>
  </div>
</template>
<script>

import Nav from '@/components/Nav.vue'
import Hero from '@/components/Hero.vue'
import PriceSection from '@/components/LandingPriceSec.vue'
import Contacts from '@/components/LandingContact.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {Nav,Hero,PriceSection,Contacts,Footer}
}
</script>