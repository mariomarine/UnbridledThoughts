<template>
  <section class="container">
    <div>
      <Nav />
		<h1> Thoughts </h1>
		<Thoughts :ub_posts=posts />
      <Footer />
    </div>
  </section>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import Thoughts from '~/components/Thoughts.vue'

import axios from 'axios';

export default {
  components: {
	Nav,
	Thoughts,
	Footer
  },
  data() {
	return {
		posts: [],
		errors: []
	}
  },
    async created() {
        try {
            const response = await axios.get('http://unbridledthoughts.com/?rest_route=/wp/v2/posts&per_page=100')
            this.posts = response.data
            console.log(this.posts)
        } catch (e) {
            console.log(e);
            this.errors.push(e)
        }
    }
}
</script>

