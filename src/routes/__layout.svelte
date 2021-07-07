<script>
	import Footer from '$lib/Footer.svelte';
	import Header from '$lib/Header.svelte';
	import '../styles/app.css';
</script>

<Header />
<main>
	<slot />
</main>
<Footer />
