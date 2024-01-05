<footer class="container">
	<div>
		<p class="made-in">
			<span class="highlight">Made in</span>
			<br />
			Lucknow
			<br />
			India.
		</p>
		<p>&copy 2023</p>
	</div>
	<div class="nav-links"></div>
</footer>

<style>
	footer {
		width: 100%;
		font-family: var(--font-pfd);
	}

	.container {
		display: flex;
		flex-direction: row;
		justify-content: space-between;

		background: var(--accent-color);
		color: var(--hl-dark);

		padding: 2rem 4rem;
	}

	.made-in {
		font-size: 2.5rem;
		font-weight: bold;

		color: var(--bg-color);
	}

	.highlight {
		font-size: 2rem;
		opacity: 0.7;
	}

	.nav-links {
	}
</style>
