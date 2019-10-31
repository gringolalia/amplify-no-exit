		<template lang="pug">
b-container
	b-row
		b-col
			img(src="../static/images/biohazard.svg" width="250px")
			h1 Electrifying Netlify
			h2 No Exit Bootstrap-Vue
			h3.mb-5 Addio Mondo Crudele
			b-button.mr-3(size="lg") Imprint Me
			b-button(variant="primary" size="lg") Elint Me
</template>
<script>
import Logo from '~/components/Logo.vue'

export default {
	components: {
		Logo
	},
	head() {
		return {
			script: [
				{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
			]
		}
	}
}
</script>
<style>
.container {
	margin: 0 auto;
	min-height: calc(100vh - 80px);
	display: flex;
	justify-content: center;
	align-items: center;
	text-align: center;
}
</style>
