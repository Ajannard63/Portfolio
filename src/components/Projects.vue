<template>
  <section class="bg-zinc-800 text-white body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap -m-4">
        <!-- Répétez ce bloc pour chaque projet -->
        <div class="p-4 md:w-1/3">
          <div class="h-full border-2 border-gray-700 border-opacity-60 rounded-lg overflow-hidden">
            <!-- <img class="lg:h-48 md:h-36 w-full object-cover object-center" src="image-projet.jpg" alt="project"> -->
            <div class="p-6">
              <h2 class="text-base font-medium text-cyan-300 mb-1">Nom du Projet</h2>
              <h1 class="title-font text-lg font-medium mb-3">Description Courte</h1>
              <p class="leading-relaxed mb-3">Description détaillée du projet. Ce que vous avez fait, les technologies utilisées, etc.</p>
              <div class="flex items-center flex-wrap ">
                <a class="text-cyan-300 inline-flex items-center md:mb-2 lg:mb-0">En savoir plus
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

<script>
export default {
  name: 'Projects',
};
</script>