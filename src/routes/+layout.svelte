<script>
	import Header from './Header.svelte';
	import '../tailwind.css';
</script>

<div class="app">
	<Header />
	<main>
		<slot />
	</main>
</div>
