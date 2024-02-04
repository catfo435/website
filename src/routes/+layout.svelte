<script>
    import "../app.css";
	import Header from "./Header.svelte";
  import Profile from "$lib/Profile.svelte"
  </script>

<Header />
<main class="flex flex-auto">
	<div class="content flex p-10 text-3xl h-full w-full">
		<div class="flex justify-center items-center"><slot /></div>
		<div class="flex justify-center items-center"><Profile /></div>
	</div>
</main>