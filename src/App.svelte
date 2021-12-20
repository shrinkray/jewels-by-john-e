<script lang="ts">
	import Tailwindcss from './Tailwindcss.svelte';
    import OverlappingPanel from "./OverlappingPanel.svelte";
	import Collections from "./Collections.svelte";
	import Newsletter from "./Newsletter.svelte";
	import Testimonial from "./Testimonial.svelte";
    import Footer from "./Footer.svelte";
</script>

<Tailwindcss />

<svelte:head>
	<title>Jewels by John E</title>
	<meta name="robots" content="noindex nofollow" />
	<html lang="en" />
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap" rel="stylesheet">
</svelte:head>

<main class="p-4 mx-auto text-center max-w-full font-sans">
    <OverlappingPanel />
	<Collections />
	<Newsletter />
	<Testimonial />
</main>
<Footer />