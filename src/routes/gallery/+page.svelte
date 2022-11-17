<script>
    import PageHeader from "$lib/PageHeader.svelte";
    import GalleryItem from "$lib/GalleryItem.svelte";
    import GalleryItemVideo from "$lib/GalleryItemVideo.svelte";
</script>

<PageHeader title="Gallery"></PageHeader>


<section class="overflow-hidden text-gray-700 pt-20">
    <div class="container px-5 py-2 mx-auto lg:pt-12 lg:px-32">
      <div class="flex flex-wrap -m-1 md:-m-2">

        <GalleryItem imgsrc="/images/gallery/tiles.jpg" alttext="Tile clean difference" ></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/carpets.jpg" alttext="carpet clean difference"></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/up.jpg" alttext="cleaning of couch difference"></GalleryItem>
        <GalleryItem imgsrc="/images/gallery/leather.jpg" alttext="cleaning of leather difference"></GalleryItem>
      </div>
    </div>
  </section>


