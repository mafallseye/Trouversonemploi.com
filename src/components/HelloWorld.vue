<script setup >
import { ref } from "vue";
defineProps({

});
const ListSkill= ref([
    {
      body: "L’empathie",
      imag: "empathie",
    },

    {
      body: "La communication",
      imag: "communication",
    },

    {
      body: "La gestion du temps",
      imag: "gestion",
    },

    {
      body: "La gestion du stress",
      imag: "stress",
    },

    {
      body: "La créativité",
      imag: "creativite",
    },

    {
      body: "L’esprit d’entreprendre",
      imag: "esprit",
    },

    {
      body: "L’audace",
      imag: "audace",
    },

    {
      body: "La motivation",
      imag: "motivation",
    },

    {
      body: "Vision",
      imag: "vision",
    },

    {
      body: "La présence",
      imag: "presence",
    },

    {
      body: "Le sens du collectif",
      imag: "sens",
    },

    {
      body: "La curiosité",
      imag: "curiosite",
    },
  ])

</script>


<template>
 
  <nav class="bg-white border-gray-200 dark:bg-gray-900">
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <a
        href="https://flowbite.com/"
        class="flex items-center space-x-3 rtl:space-x-reverse"
      >
        <img
          src="https://flowbite.com/docs/images/logo.svg"
          class="h-8"
          alt="Flowbite Logo"
        />
        <span
          class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white"
          >Trouver un emploi</span
        >
      </a>
      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
        aria-controls="navbar-default"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul
          class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700"
        >
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-white bg-blue-700 rounded-sm md:bg-transparent md:text-blue-700 md:p-0 dark:text-white md:dark:text-blue-500"
              aria-current="page"
              >Accueil</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Offres d'emploi</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Annonces</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Candidat</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-gray-900 rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Recruteur</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- ======================image======================================= -->

  <img
    class="h-auto max-w-full mb-6"
    src="../assets/Une plateforme qui permet aux candidats de rechercher et postuler gratuitements aux offres.png"
    alt="image description"
  />
  <!-- ===========================card===================================== -->

 <div class="container">
  <a
    href="#"
    class="flex flex-col items-center bg-white mb-9 md:flex-row md:max-w-full dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700"
  >
    <div class="flex flex-col justify-between p-4 leading-normal">
      <h5
        class="mb-2 text-2xl font-bold tracking-tight text-blue-900 dark:text-white"
      >
        300 000 jeunes arrivent-ils chaque année sur le marché du travail au
        Sénégal ?
      </h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
        Les formations offertes par la plupart des écoles de formation sont
        remises en causes par les entreprises qui les jugent insuffisantes pour
        les niveaux de qualification attendus. Le Déficit de communication entre
        les Écoles de formation et les entreprises empêche d'identifier de
        manière très tôt les besoins en formation ce qui constitue un frein au
        développement de l'employabilité des Jeunes.
      </p>
    </div>
    <img
      class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-130 md:rounded-none md:rounded-s-lg"
      src="../assets/emploi.png"
      alt=""
    />
  </a>
 </div>
  <!-- =====================================softs skils==================================== -->

  <div
    class="w-full p-4 mt-6 text-left bg-white sm:p-8 dark:bg-gray-800 dark:border-gray-700"
  >
    <h1 class="mb-2 text-5xl font-bold text-blue-900 dark:text-white uppercase">
      soft skills
    </h1>
    <!-- <p class="mb-5 text-base text-gray-500 sm:text-lg dark:text-gray-400">Stay up to date and move work forward with Flowbite on iOS & Android. Download the app today.</p> -->
  
  </div>

  

<div    class=  "grid mb-8  dark:border-gray-700 md:mb-12 md:grid-cols-4 bg-white dark:bg-gray-800">
    <figure    v-for="kills in  ListSkill"
    :key="kills.body"  class="flex flex-col items-center justify-center p-8 text-center    dark:bg-gray-800 dark:border-gray-700">
      
        <figcaption class="flex items-center justify-center "  >
            <img class="rounded-full w-9 h-9" v-bind:src="(`@/assets/${kills.imag}.png`)" :alt="kills.imag">
            <div      class="space-y-0.5 font-medium dark:text-white text-left rtl:text-right ms-3">
                <p
      
        class="text-blue-900 bg-gray-100 hover:bg-gray-200 focus:ring-4 focus:ring-[#2557D6]/50 focus:outline-none font-semibold text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-[#2557D6]/50 me-2 mb-2"
      >
    
        {{ kills.body }}
            </p>
            </div>
        </figcaption>    
    </figure>
   
 
</div>


<div class="container  ">
  <a
    href="#"
    class="flex mt-6 flex-col items-center bg-white mb-9 md:flex-row md:max-w-full dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700"
  >
    <div class="flex flex-col justify-between p-4 leading-normal">
      <h5
        class="mb-2 text-left text-2xl font-semibold tracking-tight text-gray-700 dark:text-white"
      >
      Les jeunes Sénégalais souffrent d’un manque criard d’opportunités d’emplois.
      </h5>
      <h5
        class="mb-2 text-left  text-xl font-semibold tracking-tight text-gray-500 dark:text-white italic"
      >
      Pour diligenter ce problème d’emploi des jeunes, il nous faut : 
      </h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
       <ul class="">
        <li class="flex md:w-full items-center text-gray-900">
            <svg class="w-3.5 h-3.5 sm:w-4 sm:h-4 me-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                <path d="M10 .5a9.5 9.5 0 1 0 9.5 9.5A9.51 9.51 0 0 0 10 .5Zm3.707 8.207-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414L9 10.586l3.293-3.293a1 1 0 0 1 1.414 1.414Z"/>
            </svg>
            Une formation de qualité qui peut permettre aux jeunes d’être opérationnels dans le bassin de l’emploi.</li>
        <li class="flex md:w-full items-center text-gray-900"> 
            <svg class="w-3.5 h-3.5 sm:w-4 sm:h-4 me-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                <path d="M10 .5a9.5 9.5 0 1 0 9.5 9.5A9.51 9.51 0 0 0 10 .5Zm3.707 8.207-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414L9 10.586l3.293-3.293a1 1 0 0 1 1.414 1.414Z"/>
            </svg> Promouvoir les métiers des nouvelles technologies.</li>
       </ul>
      </p>
    </div>
    <img
      class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-130 md:rounded-none md:rounded-s-lg"
      src="../assets/emploi1.png"
      alt=""
    />
  </a>
  <div class=" p-4 bg-white justify-center items-center text center mx-auto rounded-lg md:p-8 dark:bg-gray-800" id="statistics" role="tabpanel" aria-labelledby="statistics-tab">
            <dl class="grid max-w-screen-xl grid-cols-2 gap-8 p-4 mx-auto text-gray-900 sm:grid-cols-3 xl:grid-cols-6 dark:text-white sm:p-8">
                <div class="flex flex-col">
                  <div class="relative h-30 items-center p-3 text-md font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <dt class="mb-2 text-3xl font-extrabold">3 987</dt>
                    <dd class="text-white dark:text-gray-400">CV</dd>
  <div class="absolute inline-flex items-center justify-center w-10 h-10 text-md font-bold text-white bg-red-500 border-2 border-white rounded-full -top-6 end-15 dark:border-gray-900">20</div>
                  </div>
                  
                </div>
                <div class="flex flex-col">
                  <div class="relative  h-30 items-center p-3 text-md font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <dt class="mb-2 text-3xl font-extrabold">160</dt>
                    <dd class=" dark:text-gray-400">Recruteurs</dd>
  <div class="absolute inline-flex items-center justify-center w-10 h-10 text-md font-bold text-white bg-red-500 border-2 border-white rounded-full -top-6 end-15 dark:border-gray-900">20</div>
                  </div>
                   
                </div>
                <div class="flex flex-col">
                  <div  class="relative h-30  items-center p-3 text-md font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <dt class="mb-2 text-3xl font-extrabold">100</dt>
                    <dd class="text-white dark:text-white">Ecoles de formations</dd>
  <div class="absolute inline-flex items-center justify-center w-10 h-10 text-md font-bold text-white bg-red-500 border-2 border-white rounded-full -top-6 end-15 dark:border-gray-900">20</div>
                  </div>
          
                   
                </div>
                <div class="flex flex-col ">
                  <div class="relative  h-30 items-center p-3 text-md font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    <dt class="mb-2 text-3xl font-extrabold">87</dt>
                    <dd class="text-white dark:text-gray-400">Spécialités</dd>
  <div class="absolute inline-flex items-center justify-center w-10 h-10 text-md font-bold text-white bg-red-500 border-2 border-white rounded-full -top-6 end-15 dark:border-gray-900">20</div>
                  </div>
                   
                </div>
            </dl>
  </div>
</div>





</template>

<style scoped>

</style>
