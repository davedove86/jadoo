<script>
	import Navigation from '../components/Navigation.svelte';

</script>

<Navigation />
<main>
  <!-- Hero Section -->
  <div class="container">
    <div class="two-col-grid">
      <div>
        <p class="kicker">Best Destinations Around The World</p>
        <h1>Travel, enjoy and live a new and full life</h1>
        <p>At Jadoo, we believe that travel is more than just a journey—it’s a gateway to new experiences, cultures, and unforgettable moments. Explore the world, embrace new adventures, and create memories that will last a lifetime.</p>
        <button class="button">Find Out More</button>
      </div>
      <img class="hero-image" src="/hero-image.png" alt="Girl sitting on a suitcase">
    </div>
  </div>

  <!-- Services Section -->
   <div class="container">
    <h2>We Offer Best Services</h2>
    <div class="four-col-grid">
      <div>
        <div class="icon-container">
          <img src="/sat-dish.svg" alt  ="Satellite Dish">
        </div>
        <h3>Calculated Weather</h3>
        <p>Plan smarter with Jadoo—get weather insights for your destination and pack with confidence.</p>
      </div>
      <div>
         <div class="icon-container">
          <img src="/plane.png" alt="Plane">
        </div>
        <h3>Best Flights</h3>
        <p>Find the best flights at the best prices—Jadoo makes your journey effortless.</p>
      </div>
      <div>
         <div class="icon-container">
          <img src="/mic.png" alt="Microphone">
        </div>
        <h3>Local Events</h3>
        <p>Stay in the know with Jadoo—discover exciting local events wherever you travel.</p>
      </div>
      <div>
        <div class="icon-container">

          <img src="/cog.png" alt="Settings cog">
        </div>
        <h3>Customisation</h3>
        <p>Tailor your perfect getaway—customise every detail of your holiday with Jadoo.</p>
      </div>
    </div>
   </div>
</main>

<style>
  :global(body) {
		/* applies to <body> */
		color: #181e4b;
	}

  :global(.button) {
    background-color: #df6951;
    color: white;
    padding: 12px 24px;
    border-radius: 10px;
    border: 2px solid #df6951;
    font-weight: 600;
    cursor: pointer;
    text-align: center;
  }
  main {
    font-family: "Poppins", sans-serif;
  }
  .container {
    width: 100%;
    max-width: 1440px;
    margin: 3rem auto;
  }

  .two-col-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
    align-items: center;
    justify-items: flex-end;
  }

  h1, h2, h3 {
    font-family: "Volkhov", serif;
    font-weight: 700;
    color: #181e4b;
  }
  h1 {
    font-size: 5.25rem;
    line-height: 1.2;
    margin: 0.25rem 0;
  }

  h2 {
    text-align: center;
  }

  .kicker {
    color: #df6951;
    font-weight: 700;
    font-size: 1rem;
    text-transform: uppercase;
  }

  .hero-image {
    width: 100%;
    max-width: 600px;
  }

  .four-col-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    gap: 2rem;
    margin-top: 3rem;
    align-items: start;
    justify-content: space-between;
  }

  .icon-container {
    width: 100px;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  @media (max-width: 768px) {
    .two-col-grid {
      grid-template-columns: 1fr;
      gap: 1rem;
      justify-items: center;
    }

    h1 {
      font-size: 3.5rem;
    }
  }
</style>

