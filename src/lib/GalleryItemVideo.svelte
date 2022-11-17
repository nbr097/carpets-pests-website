<script>
// @ts-nocheck

    export let vidsrc;
    export let alttext;
</script>

<div class="flex flex-wrap w-1/3">
    <div class="w-full p-1 md:p-2">
        <!-- svelte-ignore a11y-media-has-caption -->
        <video src={vidsrc} alt={alttext} class="block object-cover object-center w-full h-full rounded-lg"></video>
    </div>
  </div>