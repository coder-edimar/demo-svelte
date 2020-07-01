<script>
	import Date from './Date.svelte';
	import List from './List.svelte';
	export let name;
	let phone = '';
</script>

<main>
	<h1>Hello {name}! Welcome back</h1>
	<Date/>
<br>
	<List/>
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

	h2 {
		color:royalblue;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>