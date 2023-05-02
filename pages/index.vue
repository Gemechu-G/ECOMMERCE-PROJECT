<template>
  <div>
    <div>
      <Auth />
    </div>
    <Nuxt />
  </div>
</template>

<script>
import Auth from '../components/auth.vue';


export default {
    name: "Index",
    layout: "admin",
    components: { Auth }
}
</script>

<style>

</style>