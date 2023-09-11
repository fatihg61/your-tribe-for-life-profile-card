<script>
  /** @type {import("@prismicio/client").Content.ProImageSlice} */
  export let slice;
</script>

<section
  data-slice-type={slice.slice_type}
  data-slice-variation={slice.variation}
>
  <img
    src={slice.primary.proimage.url}
    alt={slice.primary.proimage.alt}
    class="profile-picture"
  />
</section>

<style>
  .profile-picture {
    max-width: 150px; /* Adjust the width as needed */
    height: auto; /* Maintain aspect ratio */
    display: block; /* Center the image horizontally */
    margin: 0 auto; /* Center the image horizontally */
  }
</style>
