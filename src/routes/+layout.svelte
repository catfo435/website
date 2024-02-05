<script>
    import "../app.css";
	import Header from "./Header.svelte";
  import Profile from "$lib/Profile.svelte"
  </script>

<Header />
<main class="flex flex-auto">
	<div class="content flex p-10 text-xl h-full w-full">
		<div class="flex justify-center items-center w-1/2"><slot /></div>
		<div class="flex justify-center items-center w-1/2"><Profile /></div>
	</div>
</main>