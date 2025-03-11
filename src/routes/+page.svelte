<script>
	import '../app.css';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<div class="min-h-screen bg-black">
	<div class="m-auto max-w-4/12">
		<div class="flex justify-start gap-4">
			<h1 class="mb-7 text-5xl font-bold text-white">Hi, Ainaras there</h1>
			<h1 class="hover:animate-wave mb-7 text-5xl">👋</h1>
		</div>
		<div class="flex items-start gap-8">
			<div>
				<p class="mb-5 text-xl text-white">20 year old student based in Kaunas, Lithuania</p>
				<p class=" text-xl text-white">
					Looking to be hired in this is massive tech world that we are in, intrested in full stack
					development and the tech world around us
				</p>
			</div>

			<img src="/face.jpg" alt="My face" class="h-[200px] w-[200px] rounded-2xl" />
		</div>
	</div>
</div>

<style>
	@keyframes wave {
		0% {
			transform: rotate(0deg);
		}
		25% {
			transform: rotate(15deg);
		}
		50% {
			transform: rotate(0deg);
		}
		75% {
			transform: rotate(-15deg);
		}
		100% {
			transform: rotate(0deg);
		}
	}

	.hover\:animate-wave:hover {
		animation: wave 0.5s ease-in-out;
	}
</style>
