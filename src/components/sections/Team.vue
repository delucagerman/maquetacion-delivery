<template>
	<div class="container  mx-auto py-10 px-20 mb-16">
		<h2 class="font-sans font-extrabold text-3.5xl my-6">
			Equipo Deliveroo
		</h2>
		<section class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
			<article class="bg-red-901">
				<img class="photo" src="image/riders.jpg" alt="chica" />
				<h2
					class="text-white font-sans font-extrabold text-3.5xl my-6 ml-8"
				>
					Riders
				</h2>
				<p class="text-white font-bold mx-8">
					Conviértete en rider Deliveroo y decide con total
					flexibilidad cuándo repartir. Conseguirás buenos ingresos,
					ventajas y descuentos
				</p>
				<button
					class="h-12 rounded px-6 mt-6 bg-green-902 hover:bg-green-901 border-1 text-white font-bold m-8"
				>
					Colabora con nosotros
				</button>
			</article>
			<article class="bg-orange-901">
				<img class="photo" src="image/donuts.jpg" alt="chica" />
				<h2
					class="text-white font-sans font-extrabold text-3.5xl my-6 ml-8"
				>
					Restaurantes
				</h2>
				<p class="text-white font-bold mx-8">
					Únete a nosotros y consigue llegar a más clientes que nunca.
					Cuidamos todos los detalles, para que puedas centrarte sólo
					en la comida.
				</p>
				<button
					class="h-12 rounded px-6 mt-6 bg-green-902 hover:bg-green-901 border-1 text-white font-bold m-8"
				>
					Restaurantes
				</button>
			</article>
			<article class="bg-gray-901">
				<img class="photo" src="image/chica.jpg" alt="chica" />
				<h2
					class="text-white font-sans font-extrabold text-3.5xl my-6 ml-8"
				>
					Empleo
				</h2>
				<p class="text-white font-bold mx-8">
					Necesitamos gente como tú. Únete al equipo
				</p>
				<button
					class="h-12 rounded px-6 mt-6 bg-green-902 hover:bg-green-901 border-1 text-white font-bold m-8"
				>
					Descubre más
				</button>
			</article>
		</section>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
.photo {
	clip-path: polygon(0 0, 100% 0%, 100% 87%, 0% 100%);
}
</style>
