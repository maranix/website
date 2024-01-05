<script lang="ts">
	import Footer from '$lib/components/Footer.svelte';
</script>

<main>
	<slot />
</main>
<Footer />

<style>
	:global(:root) {
		--bg-color: rgb(36, 36, 35);
		--text-color: rgb(232, 237, 223);
		--hl-dark: rgb(51, 53, 51);
		--hl-light: rgb(207, 219, 213);
		--accent-color: rgb(245, 203, 92);

		--font-jost: jost, 'Open Sans', 'Helvetica Neue', sans-serif, system-ui, -apple-system,
			BlinkMacSystemFont, Ubuntu, Roboto, Oxygen, Cantarell;
		--font-pfd: Playfair Display, 'Open Sans', 'Helvetica Neue', sans-serif, system-ui,
			-apple-system, BlinkMacSystemFont, Ubuntu, Roboto, Oxygen, Cantarell;

		background: var(--bg-color);
		color: var(--text-color);

		font-display: swap;
		font-family: var(--font-jost);
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
	}

	:global(body) {
		margin: 0;
		padding: 0;
		max-width: 85rem;
	}
</style>
