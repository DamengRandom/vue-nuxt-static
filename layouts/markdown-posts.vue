<template>
  <div class="container mx-auto px-24 font-sans text-black">
    <div class="flex justify-between items-center">
      <h3><nuxt-link to="/">Dameng Tech Notes</nuxt-link></h3>
      <div class="flex">
        <div><nuxt-link to="/about">About</nuxt-link></div>
        <div><nuxt-link to="/contact">Contact</nuxt-link></div>
      </div>
    </div>
    <nuxt class="markdown-body" />
  </div>
</template>

<style>
  /* markdown css  */
  @import url('https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/3.0.1/github-markdown.css');

  .markdown-body {
		box-sizing: border-box;
		min-width: 200px;
		max-width: 980px;
		margin: 0 auto;
		padding: 45px;
	}

	@media (max-width: 767px) {
		.markdown-body {
			padding: 15px;
		}
	}
</style>
