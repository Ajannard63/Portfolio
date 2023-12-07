<template>
	<!-- Header -->
	<header class="bg-gradient-to-r from-zinc-900 via-gray-700 to-cyan-800 text-white py-5">
		<nav class="container mx-auto flex justify-between items-center px-4 md:px-0">
			<!-- Logo ou titre du site -->
			<div class=""><img class="h-24 bg-white p-2" src="../assets/LogoAJ.png" alt=""></div>

			<!-- Liens de navigation pour les écrans larges -->
			<div class="hidden md:flex space-x-4">
				<a href="#home" class="hover:text-red-500 transition-colors">Accueil</a>
				<a href="#about" class="hover:text-red-500 transition-colors">À Propos</a>
				<a href="#competences" class="hover:text-red-500 transition-colors">Compétences</a>
				<a href="#projet" class="hover:text-red-500 transition-colors">Projets</a>
				<!-- Ajoutez d'autres liens ici -->
			</div>

			<!-- Bouton du menu mobile -->
			<button @click="toggleMenu" class="md:hidden focus:outline-none  focus:text-white">
				<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
				</svg>
			</button>
		</nav>

		<!-- Menu mobile -->
		<div :class="{ 'flex': isMenuOpen, 'hidden': !isMenuOpen }" class="flex-col md:hidden">
			<a href="#home" class="px-4 py-2 hover:bg-red-500 transition-colors">Accueil</a>
			<a href="#about" class="px-4 py-2 hover:text-red-500 transition-colors">À Propos</a>
			<a href="#competences" class="px-4 py-2 hover:text-red-500 transition-colors">Compétences</a>
			<a href="#projet" class="px-4 py-2 hover:text-red-500 transition-colors">Projets</a>
		</div>
	</header>
</template>

<script>
export default {
	name: 'Header',
	data() {
		return {
			isMenuOpen: false,
		};
	},
	methods: {
		toggleMenu() {
			this.isMenuOpen = !this.isMenuOpen;
		}
	}
};

</script>

<style>
/* Ajoutez ici vos styles spécifiques à l'en-tête si nécessaire */
</style>

  <!-- <a href="#home" class="hover:text-red-500">Accueil</a>
				<a href="#about" class="hover:text-red-500">À Propos</a>
				<a href="#competences" class="hover:text-red-500">Compétences</a>
				<a href="#projet" class="hover:text-red-500">Portfolio</a>
				<a href="#service" class="hover:text-red-500">Services</a>
				<a href="#contact" class="hover:text-red-500">Contact</a> -->