<script>
	import NavBar from '$lib/components/NavBar.svelte';
</script>

<div class="relative">
	<!-- Nav Bar -->
	<NavBar />

	<!-- Content Area -->
	<main class="mt-20 mb-20 px-4 sm:px-6 lg:px-8">
		<slot />
	</main>
</div>
