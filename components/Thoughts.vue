<template>
	<div>
		<ul v-if="posts && posts.length">
			<li v-for="post in posts" :key="post.id">
				<a href="#">
					{{post.title.rendered}}
				</a>
				<div v-html="post.excerpt.rendered">
					{{post.excerpt.rendered}}
				</div>
			</li>
		</ul>
	</div>
</template>

<script>
import axios from 'axios';

export default {
	props: ['ub_posts'],
	computed: {
		posts() {
			return this.ub_posts
		}
	}
}
</script>

