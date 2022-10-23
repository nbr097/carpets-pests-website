<script>
	import '../app.css';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
    import Testimonials from '$lib/Testimonials.svelte';
</script>


<Nav />
<Testimonials/>
<slot />
<Footer />
