<script>
  import Header from "$lib/Header.svelte"
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Sunburst Festival | Accommodation</title>
</svelte:head>

<div class="topImage">
  <Nav />
  <Header />
</div>
<main>
  <p class="imageCredit topImageCaption">&copy; Krists Luhaers</p>
  <h2>Accommodation</h2>
  <p>Experience the ultimate music festival adventure with our tent accommodation packages! With our comfortable and convenient tents, you can immerse yourself in the festival atmosphere and stay close to all the action.</p>
  <p>Our tents are spacious and come equipped with everything you need for a comfortable stay. With comfortable beds, pillows, and blankets, you can get a good night's sleep and wake up feeling refreshed and ready for another day of music and fun.</p>

  <p>Located within the festival grounds, our tents are just a short walk away from all the stages and attractions. You won't have to worry about transportation or navigating crowds to get to the festival – you'll be right in the heart of it all.</p>
  <p>Our tents also come with a range of amenities to make your stay even more comfortable. You'll have access to clean restroom facilities, hot showers, and charging stations for your devices. We also have a dedicated staff available to assist with any needs or questions you may have during your stay.</p>

  <div class="columns">
    <div class="column">
      <img src="vonecia-carswell.jpg" alt="Man with sunglasses amongst other people smiling and dancing." />
      <p class="imageCredit">&copy; Vonecia Carswell</p>
    </div>
    <div class="column textColumn">
      <p>But the best part of our tent accommodation packages is the community. You'll be surrounded by other festival-goers who are just as excited as you are to be a part of the experience. You'll make new friends, share stories, and create memories that will last a lifetime.</p>
    </div>
  </div>

  <div class="columns bottomColumns">
    <div class="column">
      <p class="largeText">Don't miss out on this opportunity to enhance your music festival experience. Book your tent accommodation package today and get ready for an unforgettable adventure. We can't wait to see you there!</p>
      <a href="tickets">Book Now</a>
    </div>

    <div class="column">
      <img src="aranxa-esteve.jpg" alt="Three women sitting in a grass field amongst an audience." />
      <p class="imageCredit">&copy; Aranxa Esteve</p>
    </div>
  </div>
</main>

<Footer />

<style>
  .topImage {
    background-image: url("krists-luhaers.jpg");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100vw;
    height: 40vw;
    background-position: 0px -50px;
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

  .imageCredit {
    font-size: 90%;
    margin-top: -2%;
  }
  .textColumn {
    margin-top: 8%;
    line-height: 2;
  }
  .largeText {
    font-size: 150%;
    font-style: italic;
    padding-top: 8%;
    padding-bottom: 8%;
  }
  p {
    padding: 1%;
    padding-left: 3%;
    font-size: 120%;
    font-family: "Noto Sans Zanabazar Square", sans-serif;
    color: black;
  }
  main {
    margin-top: 1%;
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
  .column {
    padding: 3%;
  }

  .bottomColumns {
    padding-top: 3%;
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
