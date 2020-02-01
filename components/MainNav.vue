<template>
  <div>
    <div class="flex justify-between items-center">
      <h1 class="pt-8 mb-8 text-2xl">
        <nuxt-link
          class="no-underline text-black hover:text-grey-darkest"
          to="/">Dameng Tech Notes</nuxt-link>
      </h1>
      <div class="flex">
        <div class="mr-6 nav"><nuxt-link to="/about">About</nuxt-link></div>
        <div class="nav"><nuxt-link to="/contact">Contact</nuxt-link></div>
      </div>
    </div>
    <div class="border-b border-solid border-grey mb-8"></div>
  </div>
</template>

<style>
  .nav > a.nuxt-link-active {
    font-weight: bold;
    text-decoration: underline;
  }
</style>
