<template>
  <section class="bg-zinc-800 text-white body-font" id="projet">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap -m-4">
        <!-- Boucle pour chaque projet -->
        <div v-for="project in projects" :key="project.title" class="p-4 md:w-1/3">
          <div class="h-full border-2 border-gray-700 border-opacity-60 rounded-lg overflow-hidden">
            <!-- Mettre un v-if pour vérifier si l'image existe -->
            <img v-if="project.image" class="lg:h-48 md:h-36 w-full object-cover object-center bg-white text-black" :src="project.image" :alt="project.title">
            <div class="p-6">
              <h2 class="text-xl font-medium text-cyan-300 mb-1">{{ project.title }}</h2>
              <!-- <h1 class="title-font text-lg font-medium mb-3">Description Courte</h1> -->
              <p class="leading-relaxed mb-3">{{ project.description }}</p>
              <div class="flex items-center flex-wrap">
                <a :href="project.link" target="_blank" class="text-cyan-300 inline-flex items-center md:mb-2 lg:mb-0">En savoir plus
                  <i class="las la-arrow-right ml-2"></i> <!-- Icône Line Awesome -->
                </a>
              </div>
            </div>
          </div>
        </div>
        <!-- Fin du bloc pour chaque projet -->
      </div>
    </div>
  </section>
</template>


<script setup>
import { ref } from 'vue';
import { defineProps } from 'vue';

const props = defineProps({
  projects: Array
});
console.log(props.projects[0].image);
</script>
