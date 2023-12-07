<template>
	<section class="bg-custom bg-gray-900 text-white body-font h-screen bg-no-repeat bg-cover bg-left bg-fade-in">

		<div class="container mx-auto flex px-5 py-24 flex-col md:flex-row justify-center h-screen w-screen items-end">
			<div
				class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center text-animate">
				<h1 class="title-font sm:text-6xl text-3xl mb-4 font-medium">
					Je suis Albert Jannard un <br class="hidden lg:inline-block">
					<span class="text-red-500 uppercase">développeur web.</span>
				</h1>
				<!-- <button class="btn-contact">Contactez-moi</button> -->
			</div>
			<div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
				<!-- Ajouter une image ou un avatar personnalisé ici -->
			</div>
		</div>
	</section>
</template>
  
<script>

</script>
<style>
.bg-custom {
	background-image: url('../assets/bg.jpg');
}

.text-animate {
	opacity: 0;
	animation: textFadeIn 2s ease-in-out 1s forwards;
}

@keyframes textFadeIn {
	to {
		opacity: 1;
	}
}

.bg-fade-in {
	animation: bgFadeIn 2s ease forwards;
}

@keyframes bgFadeIn {
	from {
		opacity: 0;
	}

	to {
		opacity: 1;
	}
}
</style>

  