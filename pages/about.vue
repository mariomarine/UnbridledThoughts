<template>
  <section class="container">
    <div>
      <Nav />
	  <About />
      <Footer />
    </div>
  </section>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import About from '~/components/About.vue'

export default {
  components: {
	Nav,
	About,
	Footer
  }
}
</script>

