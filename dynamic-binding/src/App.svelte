<script>
	const name = "Dynamic binding demonstration";
	const channel = "<b>svelte-dev-ninja</b>";
	const class_name = "heading"
</script>

<main>
	<h1 class="{class_name}">{name} !</h1>
	<h4>{@html channel}</h4>
</main>

<style>
	.heading {
		color: #ff3e00;
		text-decoration: solid;
		font-weight: 500;
		font-style: italic;
	}

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