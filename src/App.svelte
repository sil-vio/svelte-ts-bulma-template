<script lang="ts">
	export let name: string;
</script>


<svelte:head>
  <style src="style.scss"></style>
</svelte:head>

<main>
	<section class="hero is-primary">
		<div class="hero-body">
		  <div class="container">
			<h1 class="title">
			  Hello {name}!
			</h1>
			<h2 class="subtitle">
				Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.
			</h2>
		  </div>
		</div>
	  </section>
</main>
