<script>
    import PageHeader from "$lib/PageHeader.svelte";
    import GalleryItem from "$lib/GalleryItem.svelte";
</script>

<svelte:head>
    <title>Gallery | Tony's Carpet & Pests</title>
    <script type="application/ld+json">{
        "@context": "http://schema.org",
        "@type": "WebSite",
          "name": "Gallary | Tony's Carpet & Pests",
          "url": "https://carpetandpests.com.au/gallery",
        }</script>
    <meta name="description" content="Here are a few before and afters of our work at Tony's Carpets & Pests">
</svelte:head>

<PageHeader title="Gallery"></PageHeader>


<section class="overflow-hidden text-gray-700 pt-20">
    <div class="container px-5 py-2 mx-auto lg:pt-12 lg:px-32">
      <div class="flex flex-wrap -m-1 md:-m-2">

        <GalleryItem imgsrc="/images/gallery/tiles.jpg" alttext="Tile clean difference" class="hover:scale-150" ></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/carpets.jpg" alttext="carpet clean difference"></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/up.jpg" alttext="cleaning of couch difference"></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/leather.jpg" alttext="cleaning of leather difference"></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/bond2.jpg" alttext="cleaning of leather difference"></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/bond3.jpg" alttext="cleaning of leather difference"></GalleryItem>

      </div>
    </div>
  </section>


