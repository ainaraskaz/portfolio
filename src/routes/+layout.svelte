<script>
	import '../app.css';
	import 'typeface-roboto';
	let { children } = $props();
</script>

<div class=" flex items-center justify-center bg-black p-10">
	<nav
		class=" mb-5 w-auto rounded-2xl border-1 bg-black py-2 text-center text-xl font-bold text-white"
	>
		<div class="items-center justify-center text-center">
			<a class="rounded-2xl border-0 px-3 py-3 hover:bg-gray-400" href="/">Home</a>
			<a class="rounded-2xl border-0 px-3 py-3 hover:bg-gray-400" href="/about">About</a>
			<a class="rounded-2xl border-0 px-3 py-3 hover:bg-gray-400" href="/projects">Projects</a>
			<a class="rounded-2xl border-0 px-3 py-3 hover:bg-gray-400" href="/contact">Tap in</a>
		</div>
	</nav>
</div>

{@render children()}
