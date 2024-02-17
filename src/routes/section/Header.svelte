<script>
	import { goto } from "$app/navigation";
    import catlogo from "$lib/cat.png"
    let navbarRoutes = ["Home","Projects"]

    /** @param {String} route */
    function handleRouteClick(route){
        switch(route){
            case "Home":
                goto("/")
                break
            default:
                goto(`/section/${route.toLowerCase()}`)
        }
    }

</script>

<header class="navbar flex flex-initial justify-center items-center text-2xl h-14 px-3.5">

    <div class="flex h-2/3 w-1/2">
        <!-- svelte-ignore a11y-missing-attribute -->
        <img src={catlogo}>
    </div>

    <div class="flex justify-end w-1/2">
        {#each navbarRoutes as route}
        <button id={route} class="routes flex justify-center items-center m-3.5" on:click={() => {handleRouteClick(route)}}>
            {route}
        </button>
        {/each}
    </div>

</header>