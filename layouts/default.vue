<template>
  <div class="bg-dark minvh-100">
    <navbar />
    <nuxt />
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'

  export default {
    components: {
      Navbar
    }
  }
</script>
