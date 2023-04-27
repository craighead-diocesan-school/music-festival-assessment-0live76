<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Sunburst Festival | Tickets</title>
</svelte:head>

<Nav />

<h2>Tickets</h2>
<p class="note">Please note that festival-goers must be 15 years of age or older.</p>
<main>
  <div>
    <form action="/action_page.php">
      <label for="admission">Festival Admission – $200 per person</label>
      <p class="formSection">
        No. Tickets <select id="ticketNum" name="ticketNum">
          <option value="0">0</option>
          <option value="200">1</option>
          <option value="400">2</option>
          <option value="600">3</option>
          <option value="800">4</option>
          <option value="1000">5</option>
          <option value="1200">6</option>
          <option value="1400">7</option>
          <option value="1600">8</option>
          <option value="1800">9</option>
          <option value="2000">10</option>
        </select>
      </p>

      <label for="tentSite">Tent Site – $15 per night</label>
      <p class="formSection">
        No. Nights Staying <select id="nightsNum" name="nightsNum">
          <option value="0">0</option>
          <option value="15">1</option>
          <option value="30">2</option>
          <option value="45">3</option>
          <option value="60">4</option>
        </select>
      </p>

      <label for="siteWithTent">Tent Site with Tent Provided – $40 per night</label>
      <p class="formSection">
        No. Nights Staying <select id="nightsNum" name="nightsNum">
          <option value="0">0</option>
          <option value="40">1</option>
          <option value="80">2</option>
          <option value="120">3</option>
          <option value="160">4</option>
        </select>
      </p>
      <div class="bookButton">
        <a href="booked">Book Now</a>
      </div>
    </form>
  </div>
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
    padding-top: 0;
  }

  main {
    padding-left: 3%;
    font-family: "Noto Sans Zanabazar Square", sans-serif;
    padding-bottom: 2%;
  }

  .formSection {
    font-size: 120%;
    padding: 3%;
    padding-bottom: 4%;
  }
  .note {
    font-size: 120%;
    padding: 3%;
    padding-top: 0;
  }
  label {
    font-size: 120%;
    font-weight: bold;
  }
  form {
    border: 2px solid black;
    padding: 2%;
    width: 80%;
  }
  .bookButton {
    padding-top: 5%;
    padding-bottom: 5%;
  }
  a {
    text-transform: uppercase;
    font-size: 120%;
    color: black;
    background-color: rgb(255, 163, 35);
    border: 1px solid black;
    border-radius: 3px;
    padding: 2%;
    padding-left: 2%;
    padding-right: 2%;
  }
  a:hover {
    text-shadow: 2px 2px white;
  }

  @media only screen and (max-width: 600px) {
    h2 {
      font-size: 5vw;
      padding-top: 10%;
    }
    .formSection {
      padding-bottom: 10%;
    }

    form {
      width: 90%;
    }
  }
</style>
