<script>
	import AboutTeamItem from '$lib/AboutTeamItem.svelte';
	import PageHeader from '$lib/PageHeader.svelte';
  </script>
  
  <svelte:head>
	<title>About Us | Tony's Carpet & Pests</title>
	<script type="application/ld+json">
	  {
		"@context": "http://schema.org",
		"@type": "WebSite",
		"name": "About Us | Tony's Carpet & Pests",
		"url": "https://carpetandpests.com.au/about",
	  }
	</script>
	<meta name="robots" content="index, follow">
	<meta name="googlebot" content="index, follow">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="description" content="Tony's Carpet & Pests is a local company based in Burpengary that offers a wide range of services from carpet cleaning, bond cleaning and pest control to a wide range of different suburbs.">
  </svelte:head>
  
  <PageHeader title="About Us" />
  
  <div class="grid overflow-hidden p-8 grid-cols-1 md:grid-cols-3 bg-slate-50 dark:bg-zinc-800 grid-rows-1 gap- grid-flow-row max-w-7xl mx-auto pt-20">
	<div class="box">
	  <ul class="list-none pt-6">
		<div class="space-y-4">
		  <div class="aspect-w-3 aspect-h-2">
			<img
			  class="object-cover shadow-lg rounded-lg"
			  src="/images/team/Tony.jpg"
			  alt="Tony / Founder"
			/>
		  </div>
		  <div class="space-y-2">
			<div class="text-lg leading-6 font-medium space-y-1">
			  <h3 class="text-zinc-800 dark:text-white">Tony</h3>
			  <p class="text-blue-600">Owner / Founder</p>
			  <p class="font-normal italic text-zinc-800 dark:text-white"></p>
			</div>
		  </div>
		</div>
	  </ul>
	</div>
  
	<div class="box col-span-2 content-center mx-auto my-auto pt-10 md:pt-0">
	  <div>
		<h1 class="text-3xl text-blue-600 px-8 pb-6 text-center overflow-hidden uppercase font-bold">
		  A message from our Owner
		</h1>
		<p class="font-medium text-zinc-800 dark:text-white text-center md:px-8">
		  Tony's carpet cleaning provides access to the best professional carpet cleaning services and Pest control in the Brisbane area for Homes, Bond Cleans, Offices, Boats, Caravans, Mobile Homes Commercial Buildings, Shops and for all other carpet cleaning needs.
		  <br /><br />
		  We ensure that our technicians are professionally trained and only use the best equipment to get the best results possible. We constantly monitor the service we provide to get you the best quality value and service.
		  <br /><br />
		  Our service provider offers competitive pricing and excellent service.
		  <br /><br />
		  We trust that you will be very pleased with the Carpet Cleaning Services our professional operators provide and would welcome any feedback to guarantee that we are always at the highest professional level you would expect from the best Carpet Cleaning Service in Brisbane.
		</p>
	  </div>
	</div>
  </div>
  
  <div class="dark:bg-zinc-800 bg-slate-50">
	<div class="mx-auto py-12 px-4 max-w-7xl sm:px-6 lg:px-8 lg:py-24">
	  <div class="space-y-12">
		<div class="space-y-5 sm:space-y-4 md:max-w-xl lg:max-w-3xl xl:max-w-none">
		  <h2 class="text-3xl font-extrabold tracking-tight sm:text-4xl overflow-hidden uppercase text-blue-600">
			Our Team
		  </h2>
		</div>
  
		<ul class="space-y-12 sm:grid sm:grid-cols-2 sm:gap-x-6 sm:gap-y-12 sm:space-y-0 lg:grid-cols-3 lg:gap-x-">
		  <!-- Example of using AboutTeamItem component -->
		  <AboutTeamItem
			name="Tony"
			role="Owner / Founder"
			subtext=""
			imageSrc="/images/team/Tony.jpg"
		  />
		  <!-- Add more AboutTeamItem components as needed -->
		</ul>
	  </div>
	</div>
  </div>
  