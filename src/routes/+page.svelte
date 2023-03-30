<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<div class="topImage">
  <Nav />
  <Header />
</div>

<main>
  <h2>General</h2>
  <p>Our festival features a diverse lineup of talented musicians from different genres, sure to satisfy every taste in music. With multiple stages set up throughout the venue, you can easily move from one act to the next, discovering new favorites and enjoying classic hits.</p>

  <div class="columns">
    <div class="column"><img src="colin-lloyd-2.jpg" alt="People facing stage at concert." /></div>
    <div class="caption column"><p>From up-and-coming artists to established headliners, we have curated an exciting lineup that will keep you dancing and singing along all day long. Our festival is the perfect opportunity to discover new music, see your favorite artists live, and make lasting memories with friends and family.</p></div>
  </div>

  <p>But the music is just the beginning. Our festival also boasts an impressive selection of food vendors, offering everything from classic festival fare to more gourmet options. You won't go hungry with the delicious treats and refreshing beverages available throughout the venue.</p>
  <p>In addition to the music and food, our festival also features a variety of activities to keep you entertained throughout the day. From art installations to merchandise booths, there is something for everyone to enjoy. You can even capture the memories with our festival photo booths and snap a selfie with your favorite artists.</p>
  <p>So don't miss out on this one-of-a-kind music festival experience. Get your tickets now and join us for a day of music, fun, and community. We can't wait to see you there!</p>
</main>

<Footer />

<style>
  .topImage {
    background-image: url("tijs-van-leur.jpg");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100vw;
    height: 40vw;
  }

  h2 {
    font-family: "Nunito", sans-serif;
    text-transform: uppercase;
    font-weight: bold;
    font-size: 200%;
    padding-left: 3%;
    padding-top: 2%;
  }

  p {
    padding: 2%;
    padding-left: 3%;
    font-size: 110%;
  }

  .columns {
    padding: 3%;
  }
  img {
    width: 60%;
    margin-left: 20%;
  }

  .caption {
    font-size: 150%;
    font-style: italic;
    padding-top: 5%;
  }
</style>
