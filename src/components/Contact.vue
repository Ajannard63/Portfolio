<template>
    <div class="bg-zinc-100 p-8 rounded-lg shadow-lg">
      <h2 class="text-2xl font-bold text-center text-indigo-700 mb-4">Me joindre :</h2>
      <ul class="list-none p-0 flex gap-8 justify-center items-center flex-col md:flex-row">
        <li class="mb-4 flex items-center">
          <i class="la la-linkedin text-blue-500 text-3xl mr-2"></i>
          <a :href="linkedin" target="_blank" class="text-blue-500 hover:text-blue-700 font-semibold text-lg">
            LinkedIn
          </a>
        </li>
        <li class="mb-4 flex items-center">
          <i class="la la-envelope text-green-500 text-3xl mr-2"></i>
          <a :href="'mailto:' + email" class="text-green-500 hover:text-green-700 font-semibold text-lg">
            Email
          </a>
        </li>
        <li class="mb-4 flex items-center">
          <i class="la la-github text-gray-700 text-3xl mr-2"></i>
          <a :href="github" target="_blank" class="text-gray-700 hover:text-gray-900 font-semibold text-lg">
            GitHub
          </a>
        </li>
        <!-- <li>
          <a href="../assets/ALBERT_CV_V2.PDF" target="_blank">Télécharger mon CV</a>
        </li> -->
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        linkedin: "https://www.linkedin.com/in/albert-jannard/",
        email: "albert@jannard.ca",
        github: "https://github.com/Ajannard63"
      };
    }
  };
  </script>
  