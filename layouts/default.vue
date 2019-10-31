	<template lang="pug">
div
	b-navbar(toggleable='lg' type='dark' variant='secondary')
		b-navbar-brand(href='#' style="font-style: normal; font-weight: 300;")
			i.fas.fa-sun.fa-lg.mr-2
			| Engenhoca Dorminhoca Opus Sete

		b-navbar-toggle(target='nav-collapse')

		b-collapse#nav-collapse(is-nav='')
			b-navbar-nav
				b-nav-item.ml-5(href='#') Tabled

				b-nav-item(href='#') Enabled

			b-navbar-nav.ml-auto
				b-nav-form
					b-form-input.mr-sm-2(size='sm', placeholder='Busqueda')

					b-button.my-2.my-sm-0(type='submit') Procurar

				b-nav-item-dropdown( text='Idioma' right)
					b-dropdown-item(href='#') Arabe

					b-dropdown-item(href='#') Farsi

					b-dropdown-item(href='#') Aramaico

					b-dropdown-item(href='#') Turco

					b-dropdown-item(href='#') Euskara

					b-dropdown-item(href='#') Ladino

				b-nav-item-dropdown(right='')

					template(v-slot:button-content='')
						| Usuário

					b-dropdown-item(href='#') Profile

					b-dropdown-item(href='#') Sign Out
	nuxt
</template>

<style>
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

.material-icons, .fa {
  vertical-align: middle;
}


</style>
