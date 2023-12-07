<template>
  <div id="app" class="bg-zinc-900 text-gray-200">
    <HeroSection />
    <Header />
    <AboutMe />
    <Skills />
    <Projects :projects="projects"/>
    <!-- <Contact />
    <Footer /> -->
  </div>
</template>

<script setup>
import Header from './components/Header.vue';
import HeroSection from './components/HeroSection.vue';
import AboutMe from './components/AboutMe.vue';
import Skills from './components/Skills.vue';
import Projects from './components/Projects.vue';
// import Contact from './components/Contact.vue';
// import Footer from './components/Footer.vue';

const projects = [
	{
		title: 'Agrotourisme Laurentides',
		description: 'Un site web réalisé dans le cadre d\'un projet scolaire. Nous avions comme mandat de créer un site web pour une entreprise fictive. Nous devions créer un site web de A à Z, incluant la création du logo, la charte graphique, le design et le développement du site web. Nous devions réaliser un site de reservation d\'emplacement de camping et de chalet dans la région des Laurentides.',
		image: '../src/assets/Agrotourisme.svg',
		link: 'https://www.google.com',
	},
	{
		title: 'Bucherons Boreal Gastronomie Rustique',
		description: 'Une application web réalisé dans le cadre d\'un projet scolaire. Nous avions comme mandat de créer un site web pour une entreprise fictive. Nous avions le mandat de créer une application web de commande en ligne pour un camion de cuisine de rue. J\ai utiliser le framework React pour réaliser ce projet.',
		image: '../src/assets/BBGR.svg',
		link: 'https://www.google.com',
	},
	{
		title: 'Audify',
		description: 'Une application web pour écouter de la musique. J\'ai réalisé ce projet dans le cadre d\'un projet scolaire. J\'ai utilisé le framework React pour réaliser ce projet. ',
		image: '../src/assets/Audify.svg',
		link: 'https://audifymusic.netlify.app/',
	},
	// {
	// 	title: 'Musée Virtuel',
	// 	description: 'Description du projet 4',
	// 	image: 'image-projet-4.jpg',
	// 	link: 'https://www.google.com',
	// },
	// {
	// 	title: 'Projet 5',
	// 	description: 'Description du projet 5',
	// 	image: 'image-projet-5.jpg',
	// 	link: 'https://www.google.com',
	// },
	// {
	// 	title: 'Projet 6',
	// 	description: 'Description du projet 6',
	// 	image: 'image-projet-6.jpg',
	// 	link: 'https://www.google.com',
	// },
];

</script>

<style>
/* Ici, vous pouvez ajouter des styles globaux ou spécifiques à l'application */
</style>
