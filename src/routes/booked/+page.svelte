<script>
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Sunburst Festival | Tickets</title>
</svelte:head>

<Nav />
<h2>Tickets</h2>
<main>
  <p><strong>Congratulations on booking your tickets!</strong> <br /> We're looking forward to seeing you!</p>
</main>
<Footer />

<style>
  h2 {
    font-family: "Nunito", sans-serif;
    text-transform: uppercase;
    font-weight: bold;
    font-size: 3vw;
    padding-left: 3%;
    color: rgb(104, 138, 144);
  }

  main {
    font-family: "Nunito", sans-serif;
    font-style: italic;
    font-size: 220%;
    padding-left: 3%;
    padding-top: 4%;
    padding-bottom: 5%;
  }

  @media only screen and (max-width: 600px) {
    .heading {
      visibility: visible;
    }
    h2 {
      font-size: 5vw;
    }
    main {
      text-align: center;
      padding-left: 0;
    }
  }
</style>
