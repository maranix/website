<script lang="ts">
	export let href: string;
	export let text: string;
</script>

<div>
	<a {href}>{text}</a>
</div>

<style>
	div {
		min-width: 100px;
	}

	a {
		color: inherit;
		text-decoration: none;

		opacity: 0.7;
		animation: opacity 200ms;
	}

	a:hover {
		opacity: 1;
		font-weight: bold;
	}
</style>
