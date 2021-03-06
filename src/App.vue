<template>
	<div id="app">
		<vHeader />
		<vInformation />
		<vActivity />
		<vNew />
		<vFooter />
	</div>
</template>
<script>
import vHeader from './components/header';
import vInformation from './components/information';
import vActivity from './components/activity';
import vNew from './components/new';
import vFooter from './components/footer';
export default {
	name: 'App',
	components: {
		vHeader,
		vInformation,
		vActivity,
		vNew,
		vFooter,
	},
};
</script>

<style lang="scss">
* {
	width: 100%;
	height: auto;
	overflow-x: hidden;
	box-sizing: border-box;
	padding: 0;
	margin: 0;
	text-decoration: none;
	outline: none;
	cursor: default;
}

@font-face {
	font-family: 'Circe';
	src: url('./assets/fonst/circle/fonts/circe.eot'); /* IE 9 Compatibility Mode */
	src: url('./assets/fonst/circle/fonts/circe.ttf') format('embedded-opentype'),
		/* IE < 9 */ url('./assets/fonst/circle/fonts/circe.woff2') format('woff2'),
		/* Super Modern Browsers */ url('./assets/fonst/circle/fonts/circe.woff')
			format('woff'),
		/* Firefox >= 3.6, any other modern browser */
			url('./assets/fonst/circle/fonts/circe.ttf') format('truetype'),
		/* Safari, Android, iOS */ url('./assets/fonst/circle/fonts/circe.svg')
			format('svg'); /* Chrome < 4, Legacy iOS */
}
@font-face {
	font-family: 'Plumb';
	src: url('./assets/fonst/plumb-black/fonts/plumb-black.otf');
	src: local('☺'),
		url('./assets/fonst/plumb-black/fonts/plumb-black.woff') format('woff'),
		url('./assets/fonst/plumb-black/fonts/plumb-black.ttf') format('truetype'),
		url('./assets/fonst/plumb-black/fonts/plumb-black.svg') format('svg');
	font-weight: normal;
	font-style: normal;
}
</style>
