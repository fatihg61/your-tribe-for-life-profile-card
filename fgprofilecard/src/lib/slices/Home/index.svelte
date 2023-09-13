<script>
  /** @type {import("@prismicio/client").Content.HomeSlice} */
  export let slice;
</script>

<section
  data-slice-type={slice.slice_type}
  data-slice-variation={slice.variation}
>
  <!-- Placeholder component for {slice.slice_type} (variation: {slice.variation})
  Slices -->
</section>

<section class="card">

  
  <img src= {slice.primary.profileimg.url} alt="Profiel foto">



  <h1>{slice.primary.title}</h1>

  <h2>{slice.primary.subtitle}</h2>


  <p>{slice.primary.paragraaf[0].text}</p>

  <a href={slice.primary.githublink.url}>Bezoek mijn Github</a>

</section>

<style>
  .card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color: #f0f0f0;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.card img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 10px;
}

.card h1 {
  font-size: 24px;
  margin-bottom: 5px;
  color: #333;
}

.card h2 {
  font-size: 18px;
  margin-bottom: 10px;
  color: #777;
}

.card p {
  font-size: 14px;
  color: #555;
  margin-bottom: 15px;
  line-height: 1.5;
}

.card a {
  display: inline-block;
  padding: 10px 20px;
  background-color: #333;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.card a:hover {
  background-color: #555;
}

</style>