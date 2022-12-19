<script>
	const name = "Sevlte world";
	const channel = "<b>svelte-dev-ninja</b>";
</script>

<main>
	<h1>Hello {name} !</h1>
	<h4>{@html channel}</h4>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>