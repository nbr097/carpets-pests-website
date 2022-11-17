<script>
// @ts-nocheck

	export let title;
	export let heroImageSrc = '/images/background/bg1.jpg';
	export let heroImageAlt = 'people practicing martial arts';
</script>

<div
	class="relative w-screen h-60 md:h-80 lg:h-96 overflow-hidden mt-20 bg-slate-50 dark:bg-zinc-800"
	style="min-height:20vh;"
>
	<img
		src={heroImageSrc}
		alt={heroImageAlt}
		class="object-cover lg:w-full lg:h-full h-70 md:h-92 min-h-60 blur"
		style="min-height:20vh;"
	/>
	<div
		class="absolute mx-auto py-36 sm:py-28 md:py-40 lg:py-48 w-screen font-bold bottom-0 inset-x-0 text-white text-center leading-4 text-6xl uppercase"
		style="min-height:20vh;"
	>
		{title}
	</div>
</div>
