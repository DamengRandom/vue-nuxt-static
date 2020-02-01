<template>
  <div class="container mx-auto px-24 font-sans text-black">
    <main-nav></main-nav>
    <nuxt class="markdown-body" />
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
  /* markdown css  */
  @import url('https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/3.0.1/github-markdown.css');

  .markdown-body {
		box-sizing: border-box;
		min-width: 200px;
		max-width: 980px;
		margin: 0 auto;
		padding: 0 45px 45px;
	}

	@media (max-width: 767px) {
		.markdown-body {
			padding: 15px;
		}
	}
</style>
