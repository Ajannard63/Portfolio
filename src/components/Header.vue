<template>
    <!-- Header -->
    <header class="container mx-auto p-5">
        <nav class="flex justify-center items-center">

            <div class="hidden md:flex space-x-4">
                <a href="#" class="hover:text-orange-500">Accueil</a>
                <a href="#" class="hover:text-orange-500">À Propos</a>
                <a href="#" class="hover:text-orange-500">Compétences</a>
                <a href="#" class="hover:text-orange-500">Portfolio</a>
                <a href="#" class="hover:text-orange-500">Services</a>
                <a href="#" class="hover:text-orange-500">Contact</a>
            </div>
            <!-- Responsive Menu Button -->
            <button class="md:hidden text-red-500">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            open: false,
        };
    },
};
</script>

<style>
/* Ajoutez ici vos styles spécifiques à l'en-tête si nécessaire */
</style>

  