<template>
	<section class="bg-zinc-900 text-white body-font" id="competences">
		<div class="container px-5 py-24 mx-auto">
			<div class="text-center mb-20">
				<h1 class="sm:text-3xl md:text-6xl font-medium mb-4 text-sky-500">Mes Compétences</h1>
			</div>
			<div>
				<!-- Icônes des compétences -->
				<h3 class="text-2xl mb-10 text-center text-zinc-400">Langages</h3>
				<div class="flex justify-center gap-2 fade-in flex-col md:flex-row items-center ">
					<i class="icon text-8xl lab la-react text-blue-400"></i> <!-- React -->
					<i class="icon text-8xl lab la-vuejs text-green-500"></i> <!-- Vue.js -->
					<i class="icon text-8xl lab la-laravel text-red-400"></i> <!-- Laravel -->
					<i class="icon text-8xl lab la-css3-alt"></i> <!-- Tailwind -->
				</div>
				<h3 class="text-2xl mb-10 text-center mt-8 text-zinc-400">Applications </h3>
				<div class="flex justify-center gap-8 fade-in flex-wrap">
					<!-- Images des compétences Adobe -->
					<img class="h-20 icon" src="../assets/photoShop.png" alt="Photoshop">
					<img class="h-20 icon" src="../assets/xd.png" alt="Adobe XD">
					<img class="h-20 icon" src="../assets/Audition.png" alt="Audition">
					<img class="h-20 icon" src="../assets/Premier.png" alt="Premiere">
					<img class="h-20 icon" src="../assets/AI.png" alt="Illustrator">
					<img class="h-20 icon" src="../assets/AE.png" alt="After Effects">
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: 'Skills',
};
</script>
<style>
.icon {
	transition: transform 0.3s ease;
}

.icon:hover {
	transform: scale(1.2);
	/* Légère augmentation de la taille au survol */
}

@keyframes fadeIn {
	from {
		opacity: 0;
		transform: translateY(20px);
	}

	to {
		opacity: 1;
		transform: translateY(0);
	}
}

.fade-in {
	animation: fadeIn 1s ease-out;
}</style>