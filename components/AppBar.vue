<template>
  <div class="  ">

    <div class=" flex justify-between items-center bg-gray-800 ">

      <div class="ml-6 text-2xl text-white hover:text-red-900 font-bold">GEBYA-YE
      </div>


      <div class="flex justify-center items-center py-2 space-x-12  ">

        <div class="relative ...">
          <div class="absolute pointer-events-auto ...">
            <svg class="absolute text-slate-400 h-7 w-2" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd"
                d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                clip-rule="evenodd" />
            </svg>
          </div>

          <input type="text" placeholder="Search" class="...">
        </div>

        <nuxt-link to="/Home" class=" text-white hover:text-gray-900">Home</nuxt-link>
        <nuxt-link to="/Carts" class=" text-white hover:text-gray-900">Cart</nuxt-link>
        <nuxt-link to="/About" class=" text-white hover:text-gray-900">About</nuxt-link>
        <!-- <nuxt-link to="/contact" class=" text-white hover:text-gray-900">Contact</nuxt-link> -->
      </div>

      <div>
        <nuxt-link to="/Profile" class="mr-6  text-white hover:text-gray-900">Sign Up/Sign In</nuxt-link>
      </div>

    </div>

  </div>
</template>

<script>
export default {
  name: 'appbar'

}
</script>

<style></style>