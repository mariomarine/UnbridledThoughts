<template>
  <section class="container">
    <div>
      <Logo />
      <Nav />
	  <Contact />
      <Footer />
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import Contact from '~/components/Contact.vue'

export default {
  components: {
	Logo,
	Nav,
	Contact,
	Footer
  }
}
</script>

