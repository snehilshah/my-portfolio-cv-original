<script>
	import Header from '$lib/Header.svelte';
	import Footer from '$lib/Footer.svelte';
	import '../app.css';

	let { children } = $props();
</script>

<Header />

<main class="pt-12 layout-md">
	{@render children()}
</main>

<Footer />
