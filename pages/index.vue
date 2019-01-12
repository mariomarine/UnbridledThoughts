<template>
  <section class="container">
    <div>
      <Logo />
      <Nav />
      <Footer />
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
	Logo,
	Nav,
	Footer
  }
}
</script>

<style>
</style>

