<template>
  <div class="  ">
    
    <div class=" flex justify-between items-center bg-gray-800 ">

      <div class="ml-6 text-2xl text-white hover:text-red-900 font-bold">LOGO
      </div>

      <div class="flex justify-center items-center py-4 space-x-12  ">
        <textarea class="w-33 h-6 p-1 bg-gray-100 border border-gray-300 rounded-md shadow-sm resize-none focus:outline-none focus:ring-blue-500 focus:border-blue-500"></textarea>
        <nuxt-link to="/Home" class=" text-white hover:text-gray-900">Home</nuxt-link>
        <nuxt-link to="/Carts" class=" text-white hover:text-gray-900">My Cart</nuxt-link>
        <nuxt-link to="/About" class=" text-white hover:text-gray-900">About</nuxt-link>
        <nuxt-link to="/contact" class=" text-white hover:text-gray-900">Contact</nuxt-link>
      </div>

      <div>
        <nuxt-link to="/Profile" class="mr-6  text-white hover:text-gray-900">Profile</nuxt-link>
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