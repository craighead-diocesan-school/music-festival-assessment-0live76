<header>
  <h1 class="title">Sunburst <br class="lineBreak" /> Festival</h1>
  <h2 class="subtitle">Welcome to the ultimate music festival experience! <br /> Get ready for a day filled with live music, great food, and unforgettable memories.</h2>
</header>

<style>
  header {
    margin-top: -3%;
  }
  br.lineBreak {
    display: inline;
  }
  h1 {
    font-family: "Montserrat Alternates", sans-serif;
    text-transform: uppercase;
    color: rgb(255, 163, 35);
    text-shadow: 3px 3px black;
    font-size: 7vw;
    padding-top: 3%;
    padding-left: 3%;
  }
  h2 {
    font-family: "Farsan", cursive;
    color: white;
    font-size: 2vw;
    margin-top: -2%;
    font-weight: normal;
    padding-left: 3%;
    text-shadow: 2px 2px black;
  }
  @media only screen and (max-width: 600px) {
    h1 {
      font-size: 8vw;
      text-align: center;
      padding-left: 0;
      padding-top: 3%;
      padding-bottom: 3%;
      background-color: white;
      position: fixed;
      width: 100%;
      top: 0;
    }

    h2 {
      font-size: 4vw;
      padding-top: 20%;
      text-shadow: none;
    }
    br.lineBreak {
      display: none;
    }
  }
</style>
