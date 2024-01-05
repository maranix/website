<script lang="ts">
	import Link from './Link.svelte';
</script>

<nav class="container">
	<a href="/">/</a>
	<div class="link-container">
		<Link href="/work" text="Work" />
		<Link href="/blog" text="Blog" />
		<Link href="/about" text="About" />
		<Link href="#contact" text="Contact" />
	</div>
</nav>

<style>
	nav {
		width: 100%;
	}

	a {
		text-decoration: none;
		color: inherit;
	}

	.container {
		display: flex;
		flex-direction: row;
		justify-content: space-between;

		font-size: 1.5rem;

		padding: 1rem 4rem;
	}

	.link-container {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
</style>
