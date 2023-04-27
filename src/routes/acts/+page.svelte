<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Sunburst Festival | Acts</title>
</svelte:head>

<div class="topImage">
  <Nav />
  <Header title="Sunburst" />
</div>
<main>
  <p class="imageCredit topImageCaption">&copy; Danny Howe</p>
  <h2>Acts</h2>
  <p>The music festival boasts an exciting lineup of talented musicians from a variety of genres, promising a diverse and entertaining experience for all attendees.</p>
  <div class="columns">
    <div class="column is-one-quarter">
      <img src="samuel-regan-asante.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Samuel Regan Asante</p>
    </div>
    <div class="column is-one-quarter">
      <img src="maxwell-collins.jpg" alt="Person on stage holding guitar facing audience." />
      <p class="imageCredit">&copy; Maxwell Collins</p>
    </div>
    <div class="column textColumn">
      <p>On the main stage, the headliners are a mix of established and up-and-coming acts, guaranteed to draw in large crowds. The first headliner is a popular rock band, known for their high-energy performances and catchy hooks. They will be followed by a chart-topping pop artist, whose upbeat and infectious hits are sure to get the crowd dancing and singing along. The final headliner is a legendary hip-hop artist, whose iconic rhymes and charismatic stage presence will bring the festival to a thrilling close.</p>
    </div>
  </div>

  <div class="columns">
    <div class="column textColumn">
      <p>On the second stage, indie bands and singer-songwriters showcase their unique styles and sounds. The performers on this stage are often the most buzzed-about acts of the festival, with a loyal and passionate following. From dreamy shoegaze bands to alternative rock acts, the second stage offers a more intimate and personal experience for music lovers looking to discover new artists.</p>
    </div>
    <div class="column">
      <img src="tony-pham.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Tony Pham</p>
    </div>
  </div>
  <div class="columns">
    <div class="column">
      <img src="aditya-chinchure.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Aditya Chinchure</p>
    </div>
    <div class="column textColumn">
      <p>The third stage is dedicated to up-and-coming artists from different genres, providing a platform for emerging talent to showcase their skills and gain exposure. This stage is a great opportunity for attendees to discover new artists and support the next generation of musicians.</p>
    </div>
  </div>

  <p>Overall, the music festival offers a diverse and exciting lineup that caters to different tastes and styles. From established headliners to emerging talent, the festival promises a memorable and thrilling musical experience for all attendees.</p>
  <div class="container">
    <a href="tickets">Book Now</a>
  </div>
</main>
<Footer />

<style>
  .topImage {
    background-image: url("/danny-howe.jpg");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100vw;
    height: 40vw;
    background-position: 0px -180px;
  }

  .topImageCaption {
    text-align: right;
    padding-top: 2%;
  }

  h2 {
    font-family: "Nunito", sans-serif;
    text-transform: uppercase;
    font-weight: bold;
    font-size: 3vw;
    padding-left: 3%;
    color: rgb(104, 138, 144);
  }
  .imageCredit {
    font-size: 90%;
    margin-top: -2%;
  }
  p {
    padding: 1%;
    padding-left: 3%;
    font-size: 120%;
    font-family: "Noto Sans Zanabazar Square", sans-serif;
    color: black;
    line-height: 2;
    padding-bottom: 2%;
  }

  main {
    margin-top: 1%;
  }

  .column {
    padding-left: 3%;
    padding-right: 3%;
  }

  .textColumn {
    padding-top: 5%;
  }

  .container {
    padding-top: 1%;
    padding-bottom: 3%;
    margin-left: 0;
  }

  a {
    border: 2px solid black;
    padding: 2%;
    border-radius: 2px;
    text-transform: uppercase;
    color: black;
    text-align: center;
    margin-left: 3%;
  }

  a:hover {
    font-style: italic;
  }

  @media only screen and (max-width: 600px) {
    .topImage {
      background-image: none;
      height: 0;
      padding-bottom: 13%;
    }
    .topImageCaption {
      visibility: hidden;
    }
    h2 {
      font-size: 5vw;
    }
    img {
      width: 90%;
      display: block;
      margin-left: auto;
      margin-right: auto;
      padding-top: 2%;
      padding-bottom: 2%;
    }
  }
</style>
