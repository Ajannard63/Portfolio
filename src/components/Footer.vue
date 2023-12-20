<template>
    <footer class="bg-gray-900 text-white p-8">
      <div class="container mx-auto flex justify-between items-center">
        <div class="flex items-center">
          <i class="la la-code text-2xl mr-2"></i>
          <span class="text-lg font-semibold">Albert Jannard</span>
        </div>
        <div class="space-x-4">
          <a :href="linkedin" target="_blank" class="text-gray-400 hover:text-white">
            <i class="la la-linkedin text-2xl"></i>
          </a>
          <a :href="github" target="_blank" class="text-gray-400 hover:text-white">
            <i class="la la-github text-2xl"></i>
          </a>
          <a :href="email" class="text-gray-400 hover:text-white">
            <i class="la la-envelope text-2xl"></i>
          </a>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    data() {
      return {
        linkedin: "https://www.linkedin.com/in/albert-jannard/",
        github: "https://github.com/Ajannard63",
        email: "mailto:albert@jannard.ca"
      };
    }
  };
  </script>
  