<template>
	<nav>
		<nuxt-link to="/"> Home </nuxt-link>
		<nuxt-link to="/about"> About </nuxt-link>
		<img class="logo" src="../UB.png" alt="Unbridled Thoughts Logo" />
		<nuxt-link to="/thoughts"> Thoughts </nuxt-link>
		<nuxt-link to="/contact"> Contact Us </nuxt-link>
	</nav>
</template>

<style>
	nav {
		margin: 0;
		padding: 0;
		display: grid;
		grid-template-columns: repeat(5, 1fr);
	}
	.logo {
		height: 50px;
	}
</style>

