<template>
	<div id="app">
		<Header />
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
import Header from './components/sections/Header';

export default {
	name: 'App',
	components: {
		Menu,
		Restaurans,
		Options,
		Kitchen,
		Team,
		Footer,
		Header,
	},
};
</script>
