<script>
    import { goto } from "$app/navigation";
    import { onMount, tick } from "svelte";
    
    let countdown = 2;
    onMount(async() => {
        while (countdown > 0) {
			await tick();
			await new Promise(resolve => setTimeout(resolve, 1000));
			countdown--;
		}
        goto('/main/home');
    });
</script>

<div class="relative h-screen flex flex-col items-center">
    <!-- Slogan -->
    <p class="absolute top-1/3 w-full text-center italic text-gray-800">
        "Keep your passwords safe!"
    </p>

    <!-- Title -->
    <h1 class="absolute bottom-20 w-full text-center text-2xl font-bold flex items-center justify-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" 
            class="w-6 h-6 fill-current">
            <path d="M19 4h-3V2h-2v2h-4V2H8v2H5c-1.103 0-2 .897-2 2v14c0 1.103.897 2 2 2h14c1.103 0 2-.897 2-2V6c0-1.103-.897-2-2-2zM5 20V7h14V6l.002 14H5z"></path>
            <path d="M7 9h10v2H7zm0 4h5v2H7z"></path>
        </svg>
        Password Manager
    </h1>
</div>
