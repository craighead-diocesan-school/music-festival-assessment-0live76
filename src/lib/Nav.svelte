<script>
  import { page } from "$app/stores"
</script>

<nav>
  <a href="/" class:current-page={$page.url.pathname == "/"}>Home</a>
  <a href="accommodation" class:current-page={$page.url.pathname.includes("accommodation")}>Accommodation</a>
  <a href="acts" class:current-page={$page.url.pathname.includes("acts")}>Acts</a>
  <a href="tickets" class:current-page={$page.url.pathname.includes("tickets")}>Tickets</a>
</nav>

<style>
  .current-page {
    color: black;
    text-shadow: 2px 2px rgb(255, 163, 35);
  }
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
    z-index: 2;
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
