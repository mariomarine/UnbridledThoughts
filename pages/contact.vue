<template>
  <section class="container">
    <div>
      <Nav />
	  <Contact />
      <Footer />
    </div>
  </section>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import Contact from '~/components/Contact.vue'

export default {
  components: {
	Nav,
	Contact,
	Footer
  }
}
</script>

