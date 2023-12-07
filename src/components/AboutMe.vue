<template>
    <!-- Section À Propos -->
    <section id="about" class="text-gray-400 bg-gray-900 body-font">
        <div class="container mx-auto flex px-5 py-24 items-center justify-center flex-col">
            <!-- Image de profil ou avatar -->
            <!-- <img class="lg:w-1/4 md:w-1/2 w-3/4 mb-10 object-cover object-center rounded-full" alt="profile"
                src="chemin_vers_image_de_profil"> -->

            <!-- Titre et texte de la section -->
            <div class="text-center lg:w-2/3 w-full">
                <h2 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-red-500">À propos de moi</h2>
                <p class="mb-8 leading-relaxed">
									Je m'appelle <span class="text-red-500">Albert Jannard</span>
                </p>
                <p class="text-justify">Je suis un développeur Web passionné avec une formation en Intégration multimédia et des compétences en PHP, MySQL et Laravel. En dehors du code, je suis fasciné par l’automobile et un grand amateur de jeux vidéo. Mes loisirs incluent la veille technologique, la mécanique automobile, le gaming et le sport, reflétant mon goût pour l’apprentissage continu et ma polyvalence.</p>
                <div class="flex justify-center">
                    <!-- Boutons ou liens d'action -->
                    <!-- <a href="#contact"
                        class="inline-flex text-white bg-orange-500 border-0 py-2 px-6 focus:outline-none hover:bg-orange-600 rounded text-lg">Contactez-moi</a> -->
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'AboutMe',
};
</script>
