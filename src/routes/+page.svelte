<script>
	import Navigation from '../components/Navigation.svelte';

</script>

<Navigation />
<main>
  <!-- Hero Section -->
  <section>
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
  </section>

  <!-- Services Section -->
  <section>
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
  </section>

  <!-- Destinations Section -->
  <section>
   <div class="container">
    <p class="text-center">Top Selling</p>
    <h2>Top Destinations</h2>
    <div class="three-col-grid">
      <div class="card">
        <div class="image-container">
          <img src="/rome.jpg" alt="City of Rome">
        </div>
        <div class="card-info-wrapper">
          <div class="card-info">
            <p>Rome, Italy</p>
            <p>£3,420</p>
          </div>
          <div class="card-length">
            <img src="/arrow.svg" alt="Arrow">
            <p>10 Days Trips</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="image-container">
          <img src="/london.jpg" alt="City of Rome">
        </div>
        <div class="card-info-wrapper">
          <div class="card-info">
            <p>London, UK</p>
            <p>£1,624</p>
          </div>
          <div class="card-length">
            <img src="/arrow.svg" alt="Arrow">
            <p>12 Days Trips</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="image-container">
          <img src="/paris.jpg" alt="City of Rome">
        </div>
        <div class="card-info-wrapper">
          <div class="card-info">
            <p>Full Europe</p>
            <p>£15,215</p>
          </div>
          <div class="card-length">
            <img src="/arrow.svg" alt="Arrow">
            <p>28 Days Trips</p>
          </div>
        </div>
      </div>

    </div>
   </div>
  </section>

  <!-- Steps section -->
  <section>
    <div class="container">
      <div class="two-col-grid">
        <div>

          <div>
            <p class="kicker">Easy and Fast</p>
            <h2 class="text-left">Book your next trip in 3 easy steps</h2>
          </div>
          <div>

            <div class="step-item">
              <div>
                <img src="/destination.svg" alt="Search icon">
              </div>
              <div class="item-text">
                <h3>Choose Destination</h3>
                <p>Find your perfect destination and let Jadoo turn your travel dreams into reality.</p>
              </div>
            </div>
            <div class="step-item">
              <div>
                <img src="/payment.svg" alt="Search icon">
              </div>
              <div class="item-text">
                <h3>Make Payment</h3>
                <p>Secure and hassle-free payments—booking your dream trip with Jadoo is just a click away.</p>
              </div>
            </div>
            <div class="step-item">
              <div>
                <img src="/taxi.svg" alt="Search icon">
              </div>
              <div class="item-text">
                <h3>Reach Airport on Selected Date</h3>
                <p>With Jadoo, travel stress-free—get to the airport on time and start your journey smoothly.</p>
              </div>
            </div>
          </div>
        </div>
        <img class="hero-image" src="/steps-image.png" alt="Travel Card Information">
      </div>
    </div>
  </section>
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

  section {
    padding: 4rem 1rem;
  }

  .container {
    width: 100%;
    max-width: 1280px;
    margin: 0 auto;
  }

  .text-center {
    text-align: center;
  }

  .text-left {
    text-align: left;
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
    font-size: 2.5rem;
    margin-bottom: 2rem;
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

  .three-col-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
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

  .icon-container img {
    width: 100%;
    height: 100%;
  }

  .image-container {
    width: 100%;
    height: 600px;
    overflow: hidden;
  }

  .card {
    border-radius: 0 0 1rem 1rem;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .card-info-wrapper {
    padding: 1rem;
  }

  .card-info {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .card-length {
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .image-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 1rem 1rem 0 0;
  }

  .step-item {
    display: flex;
    align-items: start;
    gap: 1rem;
  }

  .step-item h3 {
    font-size: 1.5rem;
    margin: 0;
  }


  @media (max-width: 768px) {
    .two-col-grid, .four-col-grid, .three-col-grid {
      grid-template-columns: 1fr;
      gap: 1rem;
      justify-items: center;
    }

    h1 {
      font-size: 3.5rem;
    }
  }
</style>

