<template>
  <section class="bg-zinc-800 text-white body-font" id="projet">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap -m-4">
        <!-- Premier projet -->
        <div class="p-4 md:w-1/3">
          <div class="h-full border-2 border-gray-700 border-opacity-60 rounded-lg overflow-hidden">
            <img class="lg:h-48 md:h-36 w-full object-cover object-center bg-white text-black"
              src="/assets/Agrotourisme.svg" alt="Agrotourisme Laurentides">
            <div class="p-6">
              <h2 class="text-xl font-medium text-cyan-300 mb-1">Agrotourisme Laurentides</h2>
              <p class="leading-relaxed mb-3">Description du projet Agrotourisme Laurentides...</p>
              <a href="https://www.google.com" target="_blank"
                class="text-cyan-300 inline-flex items-center md:mb-2 lg:mb-0">En savoir plus
                <i class="las la-arrow-right ml-2"></i>
              </a>
            </div>
          </div>
        </div>

        <!-- Deuxième projet -->
        <div class="p-4 md:w-1/3">
          <div class="h-full border-2 border-gray-700 border-opacity-60 rounded-lg overflow-hidden">
            <img class="lg:h-48 md:h-36 w-full object-cover object-center bg-white text-black" src="/assets/BBGR.svg"
              alt="Bûcherons Boréal Gastronomie Rustique">
            <div class="p-6">
              <h2 class="text-xl font-medium text-cyan-300 mb-1">Bûcherons Boréal Gastronomie Rustique</h2>
              <p class="leading-relaxed mb-3">Description du projet Bûcherons Boréal...</p>
              <a href="https://www.google.com" target="_blank"
                class="text-cyan-300 inline-flex items-center md:mb-2 lg:mb-0">En savoir plus
                <i class="las la-arrow-right ml-2"></i>
              </a>
            </div>
          </div>
        </div>

        <!-- Troisième projet -->
        <div class="p-4 md:w-1/3">
          <div class="h-full border-2 border-gray-700 border-opacity-60 rounded-lg overflow-hidden">
            <img class="lg:h-48 md:h-36 w-full object-cover object-center bg-white text-black" src="/assets/Audify.svg"
              alt="Audify">
            <div class="p-6">
              <h2 class="text-xl font-medium text-cyan-300 mb-1">Audify</h2>
              <p class="leading-relaxed mb-3">Description du projet Audify...</p>
              <a href="https://audifymusic.netlify.app/" target="_blank"
                class="text-cyan-300 inline-flex items-center md:mb-2 lg:mb-0">En savoir plus
                <i class="las la-arrow-right ml-2"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>



<script setup>
import { ref } from 'vue';
import { defineProps } from 'vue';


// console.log(props.projects[0].image);

const projects = [
  {
    title: 'Agrotourisme Laurentides',
    description: 'Un site web réalisé dans le cadre d\'un projet scolaire. Nous avions comme mandat de créer un site web pour une entreprise fictive. Nous devions créer un site web de A à Z, incluant la création du logo, la charte graphique, le design et le développement du site web. Nous devions réaliser un site de reservation d\'emplacement de camping et de chalet dans la région des Laurentides.',
    image: '/assets/Agrotourisme.svg',
    link: 'https://www.google.com',
  },
  {
    title: 'Bucherons Boreal Gastronomie Rustique',
    description: 'Une application web réalisé dans le cadre d\'un projet scolaire. Nous avions comme mandat de créer un site web pour une entreprise fictive. Nous avions le mandat de créer une application web de commande en ligne pour un camion de cuisine de rue. J\ai utiliser le framework React pour réaliser ce projet.',
    image: '/assets/BBGR.svg',
    link: 'https://www.google.com',
  },
  {
    title: 'Audify',
    description: 'Une application web pour écouter de la musique. J\'ai réalisé ce projet dans le cadre d\'un projet scolaire. J\'ai utilisé le framework React pour réaliser ce projet. ',
    image: '/assets/Audify.svg',
    link: 'https://audifymusic.netlify.app/',
  },
];
</script>
