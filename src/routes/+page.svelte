<script>
	import im1 from '$lib/assets/IMG_2519.jpeg';
	import im2 from '$lib/assets/IMG_2527.jpeg';
	import im3 from '$lib/assets/IMG_2528.jpeg';
	import im4 from '$lib/assets/IMG_2529.jpeg';
	import im5 from '$lib/assets/IMG_2532.jpeg';
	import Header from '$lib/components/Header.svelte';
	import Navigation from '$lib/components/Navigation.svelte';
</script>

<div class="flex flex-row h-screen ml-20 mr-20 gap-4">
	<Header />

	<div class="h-screen overflow-scroll">
		<div class="grid grid-flow-col grid-rows-3 grid-cols-2 gap-8">
			<div class="break-inside-avoid-column">
				<img class="aspect-square w-full" src={im1} alt="im1" />
				<h1 class="text-lg font-bold">Lorem Ipsum</h1>
				<p>hlaadfa</p>
			</div>
			<div class="break-inside-avoid-column">
				<img class="aspect-square w-full" src={im2} alt="im2" />
				<h1 class="text-lg font-bold">Lorem Ipsum</h1>
				<p>fhadgahkds</p>
			</div>
			<div class="break-inside-avoid-column">
				<img class="aspect-square w-full" src={im3} alt="im3" />
				<h1 class="text-lg font-bold">Lorem Ipsum</h1>
				<p>hlaadfa</p>
			</div>
			<div class="break-inside-avoid-column">
				<img class="aspect-square w-full" src={im4} alt="im4" />
				<h1 class="text-lg font-bold">Lorem Ipsum</h1>
				<p>hlaadfa</p>
			</div>
			<div class="break-inside-avoid-column">
				<img class="aspect-square w-full" src={im5} alt="im4" />
				<h1 class="text-lg font-bold">Lorem Ipsum</h1>
				<p>hlaadfa</p>
			</div>
		</div>
	</div>

	<Navigation />
</div>
