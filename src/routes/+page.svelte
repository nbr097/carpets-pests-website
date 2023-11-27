<script>
	import Testimonials from '$lib/Testimonials.svelte';
    import Hero from '$lib/Hero.svelte';
    import Information from '$lib/Information.svelte';
	import { comma } from 'postcss/lib/list';
</script>

<svelte:head>
    <title>Tony's Carpet & Pests</title>
    <script type="application/ld+json">{
        "@context": "http://schema.org",
        "@type": "WebSite",
          "name": "Tony's Carpet & Pests",
          "url": "https://carpetandpests.com.au",
        }</script>
        <meta name="robots" content="index,follow">
        <meta name="googlebot" content="index,follow">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Tony's Carpet & Pests is a local company based in Burpengary that offers a wide range of services from carpet cleaning, bond cleaning and pest control to a wide range of different suburbs.">
</svelte:head>

<Hero />
<Information/>
<Testimonials/>