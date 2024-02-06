<script>
    import "../app.css";
	import Header from "./section/Header.svelte";
  </script>

<div class="flex flex-col bg-[#101526] text-[#6dbecf] font-mono m-0 h-screen w-screen">
	<Header />
	<main class="flex flex-auto">
		<div class="content flex p-10 text-xl h-full w-full">
			<slot />
		</div>
	</main>
</div>