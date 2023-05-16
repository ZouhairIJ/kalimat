<script>
  import "$lib/css/reset.css";
  import "$lib/css/atom-dark-syntax.css";
  import "$lib/css/global.css";
  import Header from "$lib/components/Header.svelte";
</script>

<div class="wrapper">
  <Header />
  <main>
      <!-- <div class="bg"></div> -->
    <slot />
  </main>
</div>

<style>
  .wrapper {
    max-width: 48rem;
    margin: 0 auto;
    padding: 0 1rem;
  }
  .bg {
  /* The image used */
  background-image: url("src/lib/images/privat-0.jpg");
  

  /* Full height */
  width: 100%;
  height: 100vh; 

  /* Center and scale the image nicely */
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
}
  /* @media screen and (max-width: 600px) {} */
</style>
