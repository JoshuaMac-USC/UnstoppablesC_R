<template>
    <div class="wrapper">
    <div class="header-section">
      <Nav />
      <Hero />
    </div>
  <Regform />
  </div>
</template>
<script>


import Nav from '@/components/Nav.vue'
import Hero from '@/components/Hero.vue'
import Regform from '@/components/registerForm.vue'


export default {
  name: 'Home',
  components: {Nav, Hero,Regform}
}
</script>
