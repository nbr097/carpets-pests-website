<script>
// @ts-nocheck

    export let imgsrc;
    export let alttext;
</script>

<div class="flex flex-wrap w-1/3">
    <div class="w-full p-1 md:p-2">
      <img alt={alttext} class="block object-cover object-center w-full h-full rounded-lg"
        src={imgsrc}>
    </div>
  </div>