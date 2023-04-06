<nav>
  <a href="/">Home</a>
  <a href="accommodation">Accommodation</a>
  <a href="acts">Acts</a>
  <a href="pricing">Tickets</a>
</nav>

<style>
  a {
    color: black;
    font-family: "Farsan", cursive;
    text-transform: uppercase;
    font-size: 170%;
  }

  a:hover {
    color: rgb(255, 163, 35);
    text-shadow: 2px 2px black;
  }

  nav {
    display: flex;
    justify-content: space-between;
    padding-left: 3%;
    padding-right: 3%;
    padding-top: 2%;
    padding-bottom: 4%;
  }

  @media only screen and (max-width: 600px) {
    nav {
      position: fixed;
      background-color: white;
      bottom: 0;
      width: 100%;
      padding: 4%;
    }
    a {
      color: black;
      font-size: 150%;
    }
    a:hover {
      color: black;
      text-shadow: none;
    }
  }
</style>
