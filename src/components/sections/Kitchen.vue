<template>
	<div class="py-4  bg-gray-200">
		<div class="container mx-auto px-20">
			<h2 class="font-sans font-extrabold text-3.5xl my-6">
				Directo desde la cocina
			</h2>
			<section class="h-60 flex my-8 relative overflow-hidden">
				<div
					class="path bg-cover bg-left w-1/2 h-60"
					style="background-image: url('image/business.jpg');"
				></div>
				<div class="w-1/2 bg-white p-10 relative triangle">
					<h3 class="font-sans font-extrabold text-2xl mb-5">
						Deliveroo for Business
					</h3>
					<p>
						¿Empleados o clientes con hambre? nuestro equipo de
						cuentas corporativas te puede ayudar.
					</p>
					<button
						class="h-12 rounded px-6 mt-6 bg-green-902 hover:bg-green-901 border-1 text-white font-bold"
					>
						Preguntar
					</button>
				</div>
			</section>
			<section class="h-52 flex my-8 relative overflow-hidden">
				<div class="w-1/2 bg-white p-10">
					<h3 class="font-sans font-extrabold text-2xl mb-5">
						Tienes ya nuestra App?
					</h3>
					<p class="z-50">
						Descárgate nuestra App disponible en iOS y en Android.
					</p>
					<div class="z-0">
						<img
							style="width:280px; margin-left:-15px; margin-top:-5px"
							src="image/badges.png"
							alt="logo"
						/>
					</div>
				</div>
				<div
					class="path2 relative triangle-bottom bg-cover w-1/2 bg-center"
					style="background-image: url('image/business2.svg');"
				></div>
			</section>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
/* .path {
	clip-path: polygon(0 0, 100% 0, 95% 100%, 0% 100%);
}
.path2 {
	clip-path: polygon(5% 0, 100% 0, 100% 100%, 0% 100%);
} */
.triangle::after {
	content: '';
	width: 40px;
	height: 100%;
	background: white;
	-webkit-transform: rotate(6deg);
	transform: rotate(6deg);
	position: absolute;
	right: 0;
	top: 3px;
	z-index: 1;
	left: -14px;
}
.triangle-bottom::after {
	content: '';
	width: 40px;
	height: 104%;
	background: white;
	-webkit-transform: rotate(6deg);
	transform: rotate(6deg);
	position: absolute;
	right: 0;
	top: -4px;
	z-index: 1;
	left: -14px;
}
</style>
