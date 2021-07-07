<script context="module">
	import Info1 from '$lib/Info1.svelte';
	import Info2 from '$lib/Info2.svelte';
	import Info3 from '$lib/Info3.svelte';
	import Info4 from '$lib/Info4.svelte';
	import Info5 from '$lib/Info5.svelte';

	export const prerender = true;
</script>

<svelte:head>
	<title>Fundación Darwin</title>
</svelte:head>

<div class="flex flex-col">
	<Info1 />
	<Info2 />
	<Info3 />
	<Info4 />
	<Info5 />
</div>
