<template>
  <div class="flex justify-between items-center bg-gray-800">
    <div class="ml-6 text-2xl  text-white hover:text-red-900 font-bold">LOGO
    </div>

    <div class="flex justify-center items-center py-4 space-x-12  ">
      <nuxt-link to="/Home" class=" text-white hover:text-gray-900">Home</nuxt-link>
      <nuxt-link to="/Carts" class=" text-white hover:text-gray-900">My Cart</nuxt-link>
      <nuxt-link to="/About" class=" text-white hover:text-gray-900">About</nuxt-link>
      <nuxt-link to="/contact" class=" text-white hover:text-gray-900">Contact</nuxt-link>
    </div>

    <div>
      <nuxt-link to="/Profile" class="mr-6  text-white hover:text-gray-900">Profile</nuxt-link>
    </div>

  </div>
</template>

<script>
export default {
  name: 'appbar'

}
</script>

<style></style>