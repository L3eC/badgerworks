<script>
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>idk what to put here</title>
	<meta name="description" content="a thing which i am changing" />
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<picture>
				<img src="surprised.jpg" alt="a surprisd guy" />
			</picture>
		</span>

		to your new<br />SvelteKit app
	</h1>

	<h2>
		try editing <strong>src/routes/index.svelte</strong>
	</h2>

	<Counter />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
