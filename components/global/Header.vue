<template>
  <header>
    <div class="logo">
      <nuxt-link to="/"><img src="img/logo.svg" alt="SeyberTech Logo" width="280" /></nuxt-link>
    </div>
    <!--
    <div class="menu">
      <nav>
        <ul class="flex gap-14 text-lg">
          <li><nuxt-link to="/">Home</nuxt-link></li>
          <li><nuxt-link to="/services">Services</nuxt-link></li>
          <li><nuxt-link to="/about">About</nuxt-link></li>
          <li><nuxt-link to="/contact">Contact</nuxt-link></li>
        </ul>
      </nav>
    </div>
    <div class="cta">
      <nuxt-link :to="{ path: '/', hash: '#free-assessment' }" class="btn">Free Assessment</nuxt-link>
    </div>-->
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style lang="postcss" scoped>
header {
  @apply flex w-full place-content-center place-items-center p-8 text-center m-auto;

  .nuxt-link-exact-active {
    @apply font-bold;
  }

  li a:hover {
    @apply text-primary;
  }
}
</style>