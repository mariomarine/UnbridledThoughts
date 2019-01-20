<template>
	<nav>
		<div></div>
		<nuxt-link to="/" class="align-right"> Home </nuxt-link>
		<nuxt-link to="/about" class="align-right"> About </nuxt-link>
		<img class="logo" src="../UB.png" alt="Unbridled Thoughts Logo" />
		<nuxt-link to="/thoughts"> Thoughts </nuxt-link>
		<nuxt-link to="/contact"> Contact Us </nuxt-link>
		<div></div>
	</nav>
</template>

<style>
	nav {
		margin: 0;
		padding: 0;
		display: grid;
		grid-template-columns: repeat(7, 1fr);
	}
	.logo {
		height: 50px;
		margin-left: auto;
		margin-right: auto;
	}
	.align-right {
		text-align: right;
	}
</style>

