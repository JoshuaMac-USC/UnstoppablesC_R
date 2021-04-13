<template>
  <header class="header">
    <nav class="flex flex-jc-sb flex-ai-c">
      
      <div class="flex">
       
        <a href="/" class="header__logo">
          <img src="@/assets/logo.svg" alt="US Car rentals">
        </a>
          
        <ul class="header__links flex flex-ai-c hide-for-mobile">
          <li>
            <a href="/">Home</a>
          </li>
          <li>
            <a href="#">Services</a>
          </li>
          <li>
            <a href="#">Contact</a>
          </li>
        </ul>
        
      </div>
      
      <a href="#" class="header__menu flex-ai-c hide-for-desktop">
        <span></span>
        <span></span>
        <span></span>
      </a>

      <div class="header__cta hide-for-mobile">
        <a href="/login" class="button"> 
          <span>Login</span> </a>
        <a href="/register" class="button active">
          <span>Signup</span>
        </a>
      </div>
    </nav>
  </header>
</template>

<script>

export default {
  name: 'Nav'
}
</script>

<style lang="scss">

</style>