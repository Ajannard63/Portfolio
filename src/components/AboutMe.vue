<template>
    <section id="about" class="bg-gray-800 body-font">
        <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
            <img class="lg:w-1/4 md:w-1/2 w-3/4 mb-10 object-cover object-center rounded-full border-2 border-sky-500 shadow-lg"
                src="../assets/IMG_5299.JPG" alt="profile" style="transition: transform 0.5s ease-in-out;"
                @mouseover="animateImage" @mouseleave="resetAnimation">

            <div
                class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
                <h2 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-sky-500">À propos</h2>
                <p class="mb-8 leading-relaxed text-gray-300 text-lg">
                    🚀 <span class="font-semibold">Passionné et Innovant</span> : Développeur front-end au Québec, je mets
                    mon expertise en développement web et ma passion pour la technologie au service de vos projets.<br><br>

                    💼 <span class="font-semibold">Compétences Techniques</span> : Expérimenté en HTML, CSS, JavaScript, et
                    familiarisé avec le back-end, je crée des sites web réactifs et modernes.<br><br>

                    🌟 <span class="font-semibold">Créativité et Polyvalence</span> : Inspiré par ma passion pour
                    l'automobile et l'innovation technologique, j'apporte une perspective unique à chaque projet.<br><br>

                    🔍 <span class="font-semibold">Engagement pour l'Excellence</span> : Je suis dédié à l'amélioration
                    continue et à l'adoption des dernières tendances pour des solutions web durables.<br><br>

                    🤝 <span class="font-semibold">Partenaire Fiable</span> : Votre vision, transformée en réalité numérique
                    avec un engagement pour la qualité et la satisfaction.
                </p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'AboutMe',
    methods: {
        animateImage(event) {
            event.target.style.transform = 'scale(1.05)';
        },
        resetAnimation(event) {
            event.target.style.transform = 'scale(1)';
        }
    }
};
</script>
