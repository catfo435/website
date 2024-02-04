<script>
    import catlogo from "$lib/cat.png"
    let navbarRoutes = ["Home","CV","Projects"]
</script>

<header class="navbar flex flex-initial justify-center items-center bg-[#1a203b] text-2xl h-14 px-3.5">

    <div class="flex h-2/3 w-1/2">
        <!-- svelte-ignore a11y-missing-attribute -->
        <img src={catlogo}>
    </div>

    <div class="flex justify-end w-1/2">
        {#each navbarRoutes as route}
        <button class="routes flex justify-center items-center cursor-pointer m-3.5">
            {route}
        </button>
        {/each}
    </div>

</header>