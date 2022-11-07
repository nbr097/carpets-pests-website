<script>
	import '../app.css';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
    import Testimonials from '$lib/Testimonials.svelte';
	import Hero from '$lib/Hero.svelte';
</script>


<Nav />
<Hero />
<Testimonials/>
<slot />
<Footer />
