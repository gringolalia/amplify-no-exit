	<template lang="pug">
div
	b-navbar(toggleable='lg' type='dark' variant='secondary')
		b-navbar-brand(href='#' style="font-style: normal; font-weight: 300;")
			i.fas.fa-sun.fa-lg.mr-2
			| Engenhoca Dorminhoca Opus Sete

		b-navbar-toggle(target='nav-collapse')

		b-collapse#nav-collapse(is-nav='')
			b-navbar-nav
				b-nav-item.active.ml-5.d-none.d-lg-block(href='/') 
					i.fas.fa-university.fa-2x.mr-2
					| Wossamotta University

			b-navbar-nav.ml-auto
				//- b-nav-form.d-none.d-lg-block
				//- 	b-form-input.mr-sm-2(size='sm', placeholder='Busqueda')

				//- 	b-button.my-2.my-sm-0(type='submit') Procurar

				
				b-nav-item-dropdown.active(text='Idiomas Melanomas')
					i.fas.fa-airplane.fa-pull-left

					b-dropdown-item(href='#') Arabe

					b-dropdown-item(href='#') Farsi

					b-dropdown-item(href='#') Aramaico

					b-dropdown-item(href='#') Turco

					b-dropdown-item(href='#') Euskara

					b-dropdown-item(href='#') Ladino
					b-dropdown-item(href='#') Pawnee
					b-dropdown-item(href='#') Sentinelese
					b-dropdown-item(href='#') Swahili
					b-dropdown-item(href='#') Amharic
					b-dropdown-item(href='#') Ladhaki

				b-nav-item-dropdown.active(text="Deciduous Trees" left)
					template(v-slot:button-content='Fungo')

					b-dropdown-item(href='#') American Elm
					b-dropdown-item(href='#') Red Oak
					b-dropdown-item(href='#') Striped Maple
					b-dropdown-item(href='#') Sugar Maple
					b-dropdown-item(href='#') American Holly
					b-dropdown-item(href='#') American Sycamore
					b-dropdown-item(href='#') Black Locust
					b-dropdown-item(href='#') Black Walnut
					b-dropdown-item(href='#') Black Willow
					b-dropdown-item(href='#') Yellow Birch
					b-dropdown-item(href='#') Bald Cypress
					b-dropdown-item(href='#') Box Elder
	nuxt
</template>

<style>

@import '../assets/styles/app.css';

body, html {
  font-family: 'News Cycle', sans-serif !important;
	font-weight: 300 !important;
}

.dignity, b-navbar-brand {
  font-family: 'News Cycle', sans-serif !important;
}

	h1, h2, h3, h4, h5, h6, b-navbar-brand {
  font-family: 'News Cycle',sans-serif !important;
  font-weight: 300 !important;
	font-style: normal !important;
}

i, .material-icons {
  vertical-align: middle;
}


</style>
