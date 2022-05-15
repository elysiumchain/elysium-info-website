<script lang="ts">
    	import '../app.scss';
</script>

<svelte:head>
    <title>elysium</title>
    <meta name="description" content="Open Source Platform for Decentralized Applications"/>
</svelte:head>

<header>
</header>

<main>
	<slot />
</main>

<footer>
</footer>

<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 40px;
	}
</style>