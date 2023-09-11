<script>
  /** @type {import("@prismicio/client").Content.ProImageSlice} */
  export let slice;
</script>

<section
  data-slice-type={slice.slice_type}
  data-slice-variation={slice.variation}
>
  <img src={slice.primary.proimage.url} alt={slice.primary.proimage.alt}/>
</section>
