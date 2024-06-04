<script>
  import Header from "$lib/EnglishHeader.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<main>
  <div class="container-img">
    <img class="card-img" src="aditya-chinchure.jpg" alt="festival 1" caption="Aditya Chinchure" />
  </div>
  <div class="paragraph">
    <p>Welcome to the ultimate music festival experience! Get ready for a day filled with live music, great food, and unforgettable memories.</p>
    <p>Our festival features a diverse lineup of talented musicians from different genres, sure to satisfy every taste in music. With multiple stages set up throughout the venue, you can easily move from one act to the next, discovering new favorites and enjoying classic hits.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="danny-howe-2.jpg" alt="festival 2" caption="Danny Howe" />
  </div>
  <div class="paragraph">
    <p>From up-and-coming artists to established headliners, we have curated an exciting lineup that will keep you dancing and singing along all day long. Our festival is the perfect opportunity to discover new music, see your favorite artists live, and make lasting memories with friends and family.</p>
    <p>But the music is just the beginning. Our festival also boasts an impressive selection of food vendors, offering everything from classic festival fare to more gourmet options. You won't go hungry with the delicious treats and refreshing beverages available throughout the venue.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="hanny-naibaho.jpg" alt="festival 3" caption="Hanny Naibaho" />
  </div>
  <div class="paragraph">
    <p>In addition to the music and food, our festival also features a variety of activities to keep you entertained throughout the day. From art installations to merchandise booths, there is something for everyone to enjoy. You can even capture the memories with our festival photo booths and snap a selfie with your favorite artists.</p>
    <p>So don't miss out on this one-of-a-kind music festival experience. Get your tickets now and join us for a day of music, fun, and community. We can't wait to see you there!</p>
  </div>
  <div class="container-ticket">
    <p>Ticket</p>
    <ul class="card-ticket">
      <li>All tickets are $200 per person</li>
      <li>Festival goers must be 15 years of age or older</li>
    </ul>
  </div>
</main>

<Footer />

<style>
  main {
    color: #000000;
    background: #c4d3d4;
    font-size: 40px;
    line-height: 90px;
    text-align: center;
  }
  .paragraph {
    font-family: "Lato", sans-serif;
    margin: 60px 40px;
  }
  .container-img {
    background: #a0e1fd;
    margin: 10px;
    min-width: 1416px;
    height: auto;
  }
  .card-img {
    filter: drop-shadow(10px 10px 10px #000000);
    padding: 15px 8px 0px 8px;
  }
  .container-ticket {
    font-family: "Playfair Display SC", serif;
    background: #fc9145;
    filter: drop-shadow(10px 10px 10px #000000);
    width: 700px;
    margin: 0 auto;
  }
  @media screen and (min-width: 390px) and (max-width: 819px) {
    main {
      font-size: 10.3px;
      line-height: 23.2px;
    }
    .paragraph {
      margin: 15.5px 10.3px;
    }
    .container-img {
      margin: 2.6px;
      min-width: 364.5px;
    }
    .card-img {
      filter: drop-shadow(2.6px 2.6px 2.6px #000000);
      padding: 3.9px 2.06px 0px 2.06px;
    }
    .container-ticket {
      filter: drop-shadow(2.6px 2.6px 2.6px #000000);
      width: 161.8px;
    }
  }
  @media screen and (min-width: 390px) and (max-width: 1439px) {
    main {
      font-size: 21.7px;
      line-height: 48.8px;
    }
    .paragraph {
      margin: 32.6px 21.7px;
    }
    .container-img {
      margin: 5.5px;
      min-width: 766.4px;
    }
    .card-img {
      filter: drop-shadow(5.5px 5.5px 5.5px #000000);
      padding: 8.2px 4.3px 0px 4.3px;
    }
    .container-ticket {
      filter: drop-shadow(5.5px 5.5px 5.5px #000000);
      width: 341.7px;
    }
  }
</style>
