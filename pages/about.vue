<template>
  <section class="container">
    <div>
      <Logo />
      <Nav />
	  <About />
      <Footer />
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import About from '~/components/About.vue'

export default {
  components: {
	Logo,
	Nav,
	About,
	Footer
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

</style>

