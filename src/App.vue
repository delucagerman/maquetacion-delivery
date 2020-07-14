<template>
	<div id="app">
		<Menu />
		<Restaurans />
		<Options />
		<Kitchen />
	</div>
</template>

<script>
import Menu from './components/sections/Menu';
import Restaurans from './components/sections/Restaurans';
import Options from './components/sections/Options';
import Kitchen from './components/sections/Kitchen';

export default {
	name: 'App',
	components: {
		Menu,
		Restaurans,
		Options,
		Kitchen,
	},
};
</script>
