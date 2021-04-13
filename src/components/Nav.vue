<template>
  <header class="header">

    <div class="overlay hide-for-desktop" :class="isOpen ? 'open-overlay': ''"></div>

    <nav class="container flex flex-jc-sb flex-ai-c">
      <div class="flex">
  
        <a href="/" class="header__logo">
          <img src="@/assets/logo.svg" alt="US Car rentals">
        </a>
          
        <ul class="header__links flex flex-ai-c hide-for-mobile">
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Services</a>
          </li>
          <li>
            <a href="#">Contact</a>
          </li>
        </ul>
        
      </div>
      
      <a href="#" @click="expandMenu" class="header__toggle flex-ai-c hide-for-desktop" :class="isOpen ? 'Open' : '' ">
        <span></span>
        <span></span>
        <span></span>
      </a>

      <div class="header__cta hide-for-mobile">
        <a href="#" class="button"> 
          <span>Login</span> </a>
        <a href="#" class="button active">
          <span>Signup</span>
        </a>
      </div>

    </nav>

    <div class="header__menu hide-for-desktop" :class="isOpen? 'open-menu' : ''">
        <a href="#">Home</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </div>

  </header>

</template>

<script>

export default {
  name: 'Nav',
  data() {
    return {
      isOpen: false
    }
  },
  methods: {
    expandMenu() {
      this.isOpen = !this.isOpen

    }
  }
}
</script>

<style lang="scss">

</style>