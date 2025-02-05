<script>
	import { goto } from '$app/navigation';
</script>

<div class="fixed left-0 top-0 z-50 w-full bg-white shadow-md">
	<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
		<div class="flex h-16 items-center justify-between">
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button
				class="flex text-gray-700 hover:text-black"
				on:click={() => goto('/main/home')}
			>
				<svg
					class="h-6 w-6"
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="currentColor"
					><path d="M13.939 4.939 6.879 12l7.06 7.061 2.122-2.122L11.121 12l4.94-4.939z"
					></path></svg
				>
			</button>
			<!-- the page title -->
			<div class="flex flex-1 justify-center">
				<h1 class="text-xl font-bold text-gray-700">Add New Account</h1>
			</div>
		</div>
	</div>
</div>
