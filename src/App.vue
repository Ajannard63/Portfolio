<template>
	<div id="app" class="bg-zinc-900 text-gray-200">
		<HeroSection />
		<Header />
		<AboutMe />
		<Skills />
		<Projects />
		<Contact />
		<Footer />
		<ImportImg/>	
	</div>
</template>

<script setup>
import Header from './components/Header.vue';
import HeroSection from './components/HeroSection.vue';
import AboutMe from './components/AboutMe.vue';
import Skills from './components/Skills.vue';
import Projects from './components/Projects.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
import ImportImg from './components/ImportImg.vue';



</script>

<style>
/* Ici, vous pouvez ajouter des styles globaux ou spécifiques à l'application */
</style>
