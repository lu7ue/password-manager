<script>
	import { goto } from '$app/navigation';
</script>

<nav class="fixed left-0 top-0 z-50 w-full bg-white shadow-md">
	<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
		<div class="flex h-16 items-center justify-between">
			<!-- App title -->
			<div class="flex flex-1 justify-start">
				<button class="text-xl font-bold text-gray-700" on:click={() => goto('./home')}>Password Manager</button>
			</div>

			<!-- Add btn -->
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button
				class="mr-3 flex flex-col items-center text-gray-700 hover:text-black"
				on:click={() => goto('/others/add')}
			>
				<svg
					class="h-6 w-6"
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="currentColor"
				>
					<path d="M19 11h-6V5h-2v6H5v2h6v6h2v-6h6z"></path>
				</svg>
			</button>
			<!-- Search btn -->
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button
				class="mr-3 flex flex-col items-center text-gray-700 hover:text-black"
				on:click={() => goto('/others/search')}
			>
				<svg
					class="h-6 w-6"
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="currentColor"
					><path
						d="M10 18a7.952 7.952 0 0 0 4.897-1.688l4.396 4.396 1.414-1.414-4.396-4.396A7.952 7.952 0 0 0 18 10c0-4.411-3.589-8-8-8s-8 3.589-8 8 3.589 8 8 8zm0-14c3.309 0 6 2.691 6 6s-2.691 6-6 6-6-2.691-6-6 2.691-6 6-6z"
					></path></svg
				>
			</button>
			<!-- More btn -->
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button
				class="flex flex-col items-center text-gray-700 hover:text-black"
				on:click={() => goto('/others/more')}
			>
				<svg
					class="h-6 w-6"
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="currentColor"
					><path
						d="M10 3H4a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1zM9 9H5V5h4v4zm11-6h-6a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1zm-1 6h-4V5h4v4zm-9 4H4a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-6a1 1 0 0 0-1-1zm-1 6H5v-4h4v4zm8-6c-2.206 0-4 1.794-4 4s1.794 4 4 4 4-1.794 4-4-1.794-4-4-4zm0 6c-1.103 0-2-.897-2-2s.897-2 2-2 2 .897 2 2-.897 2-2 2z"
					></path></svg
				>
			</button>
		</div>
	</div>
</nav>
