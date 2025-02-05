<script>
	import { goto } from '$app/navigation';
</script>

<div class="fixed left-0 top-0 z-50 w-full bg-white shadow-md">
	<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
		<div class="flex h-16 items-center justify-between">
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button class="flex text-gray-700 hover:text-black" on:click={() => goto('/main/home')}>
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
				<h1 class="text-xl font-bold text-gray-700">Search</h1>
			</div>
		</div>
	</div>
</div>

<div class="pt-20">
	<div class="mx-auto max-w-4xl p-4">
		<div class="flex items-center space-x-2">
			<input
				type="text"
				placeholder="Type a keyword to search..."
				class="flex-1 rounded-lg border border-gray-300 p-2 focus:border-gray-500 focus:outline-none focus:ring-0"
				on:focus={(e) => (e.target.placeholder = '')}
				on:blur={(e) => (e.target.placeholder = 'Type a keyword to search...')}
			/>
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button
				class="flex items-center rounded-lg bg-gray-200 p-2 text-gray-700 hover:text-black"
				on:click={() => goto('')}
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
		</div>
		<div class="mt-8 text-center text-gray-600">There are 0 accounts in total</div>
	</div>
</div>
