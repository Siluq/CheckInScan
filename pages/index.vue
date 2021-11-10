<template>
  <nav class="bg-gradient-to-r from-blue-900 to-blue-400">
    <div class="flex items-center justify-between flex-wrap p-6 mx-36">
      <div class="flex items-center flex-shrink-0 text-white">
        <span class="font-bold text-xl">Check-in</span>
      </div>
      <button class="lg:hidden inline-flex items-center justify-center text-white h-10 w-10 rounded-md outline-none focus:outline-none">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
      <div class="w-full block flex-grow sm:flex sm:items-center sm:w-auto">
          <div class="text-sm sm:flex-grow">
            <ul>
              <li
                href="#"
                class="block mt-4 sm:inline-block sm:mt-0 text-white hover:text-white mr-4">
                Inicio
              </li>
              <li
                href="#"
                class="block mt-4 sm:inline-block sm:mt-0 text-white hover:text-white mr-4">
                Servios
              </li>
              <li
                href="#"
                class="block mt-4 sm:inline-block sm:mt-0 text-white hover:text-white mr-4">
                Faq
              </li>
              <li
                href="#"
                class="block mt-4 sm:inline-block sm:mt-0 text-white hover:text-white">
                Precios
              </li>
            </ul>
            </div>
            <div>
              <li
              href="#"
              class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-blue-500 hover:bg-white mt-4 md:mt-0">
              Login
              </li>
          </div>
        </div>
      </div>

      <!-- Mobile menu button -->
      <div class="sm:hidden flex items-center">
        <button class="outline-none mobile-menu-button">
          <svg
            class="w-6 h-6 text-gray-500"
            x-show="!showMenu"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
          <path d="M4 6h16M4 12h16M4 18h16"></path>
          </svg>
        </button>
      </div>

      <!-- Mobile menu -->
      <div class="hidden mobile-menu">
        <ul class="">
          <li class="active"><a href="index.html" class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold">Home</a></li>
          <li><a href="#services" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Services</a></li>
          <li><a href="#about" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">About</a></li>
          <li><a href="#contact" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Contact Us</a></li>
        </ul>
      </div>
    </nav>
</template>

<script>
export default {}
</script>
