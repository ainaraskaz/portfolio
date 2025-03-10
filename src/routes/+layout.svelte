<script>
	import '../app.css';
	let { children } = $props();
</script>

<div class="min-h-screen bg-black">
	<div class=" flex items-center justify-center p-6">
		<nav class=" w-auto rounded-2xl border-1 bg-black p-4 text-center text-xl font-bold text-white">
			<div class="items-center justify-center text-center">
				<a class="rounded-2xl border-0 p-3 hover:bg-gray-400" href="/">Namai namuciai </a>
				<a class=" rounded-2xl border-0 p-3 hover:bg-gray-400" href="/about"
					>Mentas kad klausineji APIE MANE</a
				>
				<a class=" rounded-2xl border-0 p-3 hover:bg-gray-400" href="/projects"
					>Dabar gerai pagalvok ar ktu studentas tures PROJEKTU</a
				>
				<a class="rounded-2xl border-0 p-3 hover:bg-gray-400" href="/contact">tap in</a>
			</div>
		</nav>
	</div>
</div>
{@render children()}
