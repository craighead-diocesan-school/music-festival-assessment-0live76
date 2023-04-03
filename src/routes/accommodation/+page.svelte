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
  <h2>Accommodation</h2>
  <p>Experience the ultimate music festival adventure with our tent accommodation packages! With our comfortable and convenient tents, you can immerse yourself in the festival atmosphere and stay close to all the action</p>
  <p>Our tents are spacious and come equipped with everything you need for a comfortable stay. With comfortable beds, pillows, and blankets, you can get a good night's sleep and wake up feeling refreshed and ready for another day of music and fun.</p>
  <div class="columns">
    <div class="column">
      <img class="concertImage" src="colin-lloyd-2.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">Colin Llyod</p>
    </div>
    <div class="column is-half">
      <img src="danny-howe-2.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">Danny Howe</p>
    </div>
    <div class="column">
      <img class="concertImage" src="colin-lloyd.jpg" alt="People facing stage at concert." />
      <p class="imageCredit">Colin Llyod</p>
    </div>
  </div>
  <p>Located within the festival grounds, our tents are just a short walk away from all the stages and attractions. You won't have to worry about transportation or navigating crowds to get to the festival – you'll be right in the heart of it all.</p>
  <p>Our tents also come with a range of amenities to make your stay even more comfortable. You'll have access to clean restroom facilities, hot showers, and charging stations for your devices. We also have a dedicated staff available to assist with any needs or questions you may have during your stay.</p>
  <p>But the best part of our tent accommodation packages is the community. You'll be surrounded by other festival-goers who are just as excited as you are to be a part of the experience. You'll make new friends, share stories, and create memories that will last a lifetime.</p>
  <p>Don't miss out on this opportunity to enhance your music festival experience. Book your tent accommodation package today and get ready for an unforgettable adventure. We can't wait to see you there!</p>
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

  /* .largeText {
    font-size: 150%;
    font-style: italic;
    padding-top: 8%;
  } */
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
</style>
