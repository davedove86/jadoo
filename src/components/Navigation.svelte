<div class="container">
  <nav>
      <img src="/logo.svg" alt="Jadoo Logo">
      <ul>
          <li><a href="/">Destinations</a></li>
          <li><a href="/">Hotels</a></li>
          <li><a href="/">Flights</a></li>
          <li><a href="/">Bookings</a></li>
          <button class="button">Login</button>

      </ul>
  </nav>
</div>

<style>

  .container {
    width: 100%;
    max-width: 1440px;
    margin: 0 auto;
  }

  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #fff;
    font-family: "Poppins", sans-serif;
  }

  img {
    width: 100px;
  }

  ul {
    display: flex;
    align-items: center;
    list-style: none;
  }

  li {
    margin-right: 1.5rem;
  }

  a {
    text-decoration: none;
    color: #181e4b;
    font-weight: 400;
    transition: color 0.3s;
  }

  a:hover {
    color: #df6951;
  }

  @media (max-width: 768px) {
    nav {
      flex-direction: column;
      justify-content: center;
    }

    li {
    margin-right: 1rem;
  }
  }
</style>
