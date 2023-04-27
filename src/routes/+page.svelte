<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Sunburst Festival | Home</title>
</svelte:head>

<div class="topImage">
  <Nav />
  <Header title="Sunburst" />
</div>
<main>
  <p class="imageCredit topImageCaption">&copy; Tjis Van Leur</p>
  <h2>General</h2>
  <p>Our festival features a diverse lineup of talented musicians from different genres, sure to satisfy every taste in music. With multiple stages set up throughout the venue, you can easily move from one act to the next, discovering new favorites and enjoying classic hits.</p>
  <p>From up-and-coming artists to established headliners, we have curated an exciting lineup that will keep you dancing and singing along all day long. Our festival is the perfect opportunity to discover new music, see your favorite artists live, and make lasting memories with friends and family.</p>
  <div class="columns">
    <div class="column">
      <img src="colin-lloyd-2.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Colin Llyod</p>
    </div>
    <div class="column is-half">
      <img src="danny-howe-2.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Danny Howe</p>
    </div>
    <div class="column">
      <img src="colin-lloyd.jpg" alt="DJ holding a microphone in the air." />
      <p class="imageCredit">&copy; Colin Llyod</p>
    </div>
  </div>
  <p>But the music is just the beginning. Our festival also boasts an impressive selection of food vendors, offering everything from classic festival fare to more gourmet options. You won't go hungry with the delicious treats and refreshing beverages available throughout the venue.</p>
  <p>In addition to the music and food, our festival also features a variety of activities to keep you entertained throughout the day. From art installations to merchandise booths, there is something for everyone to enjoy. You can even capture the memories with our festival photo booths and snap a selfie with your favorite artists.</p>

  <div class="columns bottomColumns">
    <div class="column">
      <p class="largeText">So don't miss out on this one-of-a-kind music festival experience. Get your tickets now and join us for a day of music, fun, and community. We can't wait to see you there!</p>
      <a href="tickets">Book Now</a>
    </div>

    <div class="column">
      <img src="james-genchi.jpg" alt="People facing stage with colourful confetti." />
      <p class="imageCredit">&copy; James Genchi</p>
    </div>
  </div>
</main>

<Footer />

<style>
  .topImage {
    background-image: url("/tijs-van-leur.jpg");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 120vw;
    height: 40vw;
    background-position: 0px -120px;
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
    padding-top: 2%;
    color: rgb(104, 138, 144);
  }
  main {
    margin-top: 1%;
  }

  p {
    padding: 1%;
    padding-left: 3%;
    font-size: 120%;
    font-family: "Noto Sans Zanabazar Square", sans-serif;
    color: black;
  }

  .column {
    padding: 3%;
  }

  .imageCredit {
    font-size: 90%;
    margin-top: -2%;
  }

  .bottomColumns {
    padding-top: 3%;
  }

  .largeText {
    font-size: 150%;
    font-style: italic;
    padding-top: 8%;
    padding-bottom: 8%;
  }

  a {
    border: 2px solid black;
    padding: 3%;
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
