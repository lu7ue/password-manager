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
				<h1 class="text-xl font-bold text-gray-700">Settings</h1>
			</div>
		</div>
	</div>
</div>

<div class="pt-20">
	<div class="mx-auto max-w-4xl p-4">
		<!-- First Card -->
		<div class="mb-4 rounded-lg bg-white p-4 shadow-md">
			<div class="flex items-center justify-between py-2 border-b border-gray-300">
				Import Data
				<!-- svelte-ignore a11y_consider_explicit_label -->
				<button
					class="float-right text-gray-700 hover:text-black"
					on:click={() => goto('/main/home')}
				>
					<svg
						class="h-6 w-6"
						xmlns="http://www.w3.org/2000/svg"
						fill="currentColor"
						viewBox="0 0 24 24"
						><path d="M10.707 17.707 16.414 12l-5.707-5.707-1.414 1.414L13.586 12l-4.293 4.293z"
						></path></svg
					>
				</button>
			</div>
			<div class="flex items-center justify-between py-2 border-b border-gray-300">
				Export Data
				<!-- svelte-ignore a11y_consider_explicit_label -->
				<button
					class="float-right text-gray-700 hover:text-black"
					on:click={() => goto('/main/home')}
				>
					<svg
						class="h-6 w-6"
						xmlns="http://www.w3.org/2000/svg"
						fill="currentColor"
						viewBox="0 0 24 24"
						><path d="M10.707 17.707 16.414 12l-5.707-5.707-1.414 1.414L13.586 12l-4.293 4.293z"
						></path></svg
					>
				</button>
			</div>
			<div class="flex items-center justify-between py-2 border-b border-gray-300">
				Change Password
				<!-- svelte-ignore a11y_consider_explicit_label -->
				<button
					class="float-right text-gray-700 hover:text-black"
					on:click={() => goto('/main/home')}
				>
					<svg
						class="h-6 w-6"
						xmlns="http://www.w3.org/2000/svg"
						fill="currentColor"
						viewBox="0 0 24 24"
						><path d="M10.707 17.707 16.414 12l-5.707-5.707-1.414 1.414L13.586 12l-4.293 4.293z"
						></path></svg
					>
				</button>
			</div>
			<div class="flex items-center justify-between py-2">
				Random Password Generator
				<!-- svelte-ignore a11y_consider_explicit_label -->
				<button
					class="float-right text-gray-700 hover:text-black"
					on:click={() => goto('/main/home')}
				>
					<svg
						class="h-6 w-6"
						xmlns="http://www.w3.org/2000/svg"
						fill="currentColor"
						viewBox="0 0 24 24"
						><path d="M10.707 17.707 16.414 12l-5.707-5.707-1.414 1.414L13.586 12l-4.293 4.293z"
						></path></svg
					>
				</button>
			</div>
		</div>

		<!-- Separate Cards -->
		<div class="mb-4 rounded-lg bg-white p-4 shadow-md">
			Wipe All Local Data
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button
				class="float-right text-gray-700 hover:text-black"
				on:click={() => goto('/main/home')}
			>
				<svg
					class="h-6 w-6"
					xmlns="http://www.w3.org/2000/svg"
					fill="currentColor"
					viewBox="0 0 24 24"
					><path d="M10.707 17.707 16.414 12l-5.707-5.707-1.414 1.414L13.586 12l-4.293 4.293z"
					></path></svg
				>
			</button>
		</div>
		<div class="rounded-lg bg-white p-4 shadow-md">
			About Us
			<!-- svelte-ignore a11y_consider_explicit_label -->
			<button
				class="float-right text-gray-700 hover:text-black"
				on:click={() => goto('/main/home')}
			>
				<svg
					class="h-6 w-6"
					xmlns="http://www.w3.org/2000/svg"
					fill="currentColor"
					viewBox="0 0 24 24"
					><path d="M10.707 17.707 16.414 12l-5.707-5.707-1.414 1.414L13.586 12l-4.293 4.293z"
					></path></svg
				>
			</button>
		</div>
	</div>
</div>
