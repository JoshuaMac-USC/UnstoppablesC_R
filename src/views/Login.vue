<template>
    <div class="wrapper">
    <div class="header-section">
      <Nav />
      <Hero />
    </div>
  <Loginform />
  </div>
</template>
<script>


import Nav from '@/components/Nav.vue'
import Hero from '@/components/Hero.vue'
import Loginform from '@/components/loginForm.vue'


export default {
  name: 'Home',
  components: {Nav, Hero,Loginform}
}
</script>
