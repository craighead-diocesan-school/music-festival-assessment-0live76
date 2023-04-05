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
  <Header />
</div>
<main>
  <h2>General</h2>
  <p>Our festival features a diverse lineup of talented musicians from different genres, sure to satisfy every taste in music. With multiple stages set up throughout the venue, you can easily move from one act to the next, discovering new favorites and enjoying classic hits.</p>
  <p>From up-and-coming artists to established headliners, we have curated an exciting lineup that will keep you dancing and singing along all day long. Our festival is the perfect opportunity to discover new music, see your favorite artists live, and make lasting memories with friends and family.</p>
  <div class="columns">
    <div class="column">
      <img class="concertImage" src="colin-lloyd-2.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Colin Llyod</p>
    </div>
    <div class="column is-half">
      <img src="danny-howe-2.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Danny Howe</p>
    </div>
    <div class="column">
      <img class="concertImage" src="colin-lloyd.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">&copy; Colin Llyod</p>
    </div>
  </div>
  <p>But the music is just the beginning. Our festival also boasts an impressive selection of food vendors, offering everything from classic festival fare to more gourmet options. You won't go hungry with the delicious treats and refreshing beverages available throughout the venue.</p>
  <p>In addition to the music and food, our festival also features a variety of activities to keep you entertained throughout the day. From art installations to merchandise booths, there is something for everyone to enjoy. You can even capture the memories with our festival photo booths and snap a selfie with your favorite artists.</p>

  <div class="columns bottom">
    <div class="column">
      <p class="largeText">So don't miss out on this one-of-a-kind music festival experience. Get your tickets now and join us for a day of music, fun, and community. We can't wait to see you there!</p>
    </div>

    <div class="column">
      <img src="james-genchi.jpg" alt="People facing stage with colourful confetti." />
      <p class="imageCredit">James Genchi</p>
    </div>
  </div>
</main>

<Footer />

<style>
  .topImage {
    background-image: url("tijs-van-leur.jpg");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 120vw;
    height: 40vw;
    background-position: 0px -120px;
  }

  h2 {
    font-family: "Nunito", sans-serif;
    text-transform: uppercase;
    font-weight: bold;
    font-size: 250%;
    padding-left: 3%;
    padding-top: 2%;
    color: rgb(104, 138, 144);
  }

  p {
    padding: 2%;
    padding-left: 3%;
    font-size: 110%;
  }

  .imageCredit {
    font-size: 90%;
    margin-top: -2%;
  }

  .largeText {
    font-size: 150%;
    font-style: italic;
    padding-top: 8%;
  }
  p {
    padding: 1%;
    padding-left: 3%;
    font-size: 110%;
    font-family: "Noto Sans Zanabazar Square", sans-serif;
    color: black;
  }

  .column {
    padding: 3%;
  }

  .bottom {
    padding-top: 3%;
  }
</style>
