<script>
	import '../app.css';
	let { children } = $props();
</script>

<div class=" flex items-center justify-center">
	<nav class=" w-8/12 rounded-2xl bg-gray-500 p-4 text-center text-xl font-bold text-blue-900">
		<div class="items-center justify-center text-center">
			<a class=" p-3" href="/">Namai namuciai </a>
			<a class=" p-3" href="/about">Mentas kad klausineji APIE MANE</a>
			<a class=" p-3" href="/projects">Dabar gerai pagalvok ar ktu studentas tures projektu</a>
			<a class="p-3" href="/contec">tap in</a>
		</div>
	</nav>
</div>
{@render children()}
