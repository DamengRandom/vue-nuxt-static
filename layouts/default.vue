<template>
  <div class="container mx-auto px-24 font-sans text-black">
    <main-nav></main-nav>
    <nuxt />
  </div>
</template>

<script>
  import MainNav from "../components/MainNav";

  export default {
    components: {
      MainNav
    }
  }
</script>

<style>
  .container-inner {
    max-width: 980px;
  }
  
</style>
