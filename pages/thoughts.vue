<template>
  <section class="container">
    <div>
      <Logo />
      <Nav />
	  <Thoughts />
      <Footer />
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import Thoughts from '~/components/Thoughts.vue'

export default {
  components: {
	Logo,
	Nav,
	Thoughts,
	Footer
  }
}
</script>

