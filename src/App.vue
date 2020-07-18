<template>
	<div id="app">
		<Menu />
		<Restaurans />
		<Options />
		<Kitchen />
		<Team />
		<Footer />
	</div>
</template>

<script>
import Menu from './components/sections/Menu';
import Restaurans from './components/sections/Restaurans';
import Options from './components/sections/Options';
import Kitchen from './components/sections/Kitchen';
import Team from './components/sections/Team';
import Footer from './components/sections/Footer';

export default {
	name: 'App',
	components: {
		Menu,
		Restaurans,
		Options,
		Kitchen,
		Team,
		Footer,
	},
};
</script>
