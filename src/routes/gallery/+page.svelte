<script>
  import PageHeader from "$lib/PageHeader.svelte";
  import GalleryItem from "$lib/GalleryItem.svelte";
</script>

<svelte:head>
  <title>Gallery | Tony's Carpet & Pests</title>
  <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "WebSite",
      "name": "Gallery | Tony's Carpet & Pests",
      "url": "https://carpetandpests.com.au/gallery"
    }
  </script>
  <meta name="description" content="Here are a few before and afters of our work at Tony's Carpets & Pests">
  <meta name="robots" content="index, follow">
  <meta name="googlebot" content="index, follow">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</svelte:head>

<PageHeader title="Gallery" />

<section class="overflow-hidden text-gray-700 pt-20">
  <div class="container px-5 py-2 mx-auto lg:pt-12 lg:px-32">
    <div class="flex flex-wrap -m-1 md:-m-2">
      <!-- Iterating through an array of image objects would be more scalable -->
      {#each imageList as image (image.id)}
        <GalleryItem
          imgsrc={image.src}
          alttext={image.alt}
          class="hover:scale-150"
        ></GalleryItem>
      {/each}
    </div>
  </div>
</section>

<script>
  // You might have an array of images with src and alt properties
  let imageList = [
    {
      id: 1,
      src: "/images/gallery/tiles.jpg",
      alt: "Tile clean difference"
    },
    {
      id: 2,
      src: "/images/gallery/carpets.jpg",
      alt: "carpet clean difference"
    },
    // Add more images similarly
  ];
</script>
