<script>
    import "../../app.css";
  import Profile from "$lib/Profile.svelte"
  </script>

<main class="flex flex-auto">
	<div class="content flex p-10 text-xl h-full w-full">
		<div class="flex justify-center items-center w-2/3 px-20"><slot /></div>
		<div class="flex justify-center items-center w-1/3"><Profile /></div>
	</div>
</main>