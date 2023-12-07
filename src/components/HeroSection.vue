<template>
    <section class="bg-gray-900 text-white body-font">
        <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
            <!-- Conteneur pour le titre et le bouton -->
            <div
                class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
                <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-white">
                    Je suis un <br class="hidden lg:inline-block"><span class="text-red-500 uppercase">développer <br
                            class="hidden lg:inline-block"> web.</span>
                </h1>

                <div class="flex justify-center">
                    <button
                        class="inline-flex text-white bg-red-500 border-0 py-.5 px-1 focus:outline-none hover:bg-orange-600 rounded text-sm">Contactez-moi</button>
                </div>
            </div>
            <!-- Conteneur pour l'image ou l'avatar -->
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
                <!-- <img class="object-cover object-center rounded" alt="hero" src="path_to_image"> -->
            </div>
        </div>
    </section>
</template>
  
<script>
export default {
    name: 'HeroSection',
};
</script>
  

  