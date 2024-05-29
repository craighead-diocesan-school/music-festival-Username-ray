<script>
  import Header from "$lib/EnglishHeader.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<main>
  <div class="container-img">
    <img class="card-img" src="aranxa-esteve.jpg" alt="&copy; Aranxa Esteve" />
  </div>
  <div class="paragraph">
    <p>The music festival boasts an exciting lineup of talented musicians from a variety of genres, promising a diverse and entertaining experience for all attendees.</p>
    <p>On the main stage, the headliners are a mix of established and up-and-coming acts, guaranteed to draw in large crowds. The first headliner is a popular rock band, known for their high-energy performances and catchy hooks. They will be followed by a chart-topping pop artist, whose upbeat and infectious hits are sure to get the crowd dancing and singing along. The final headliner is a legendary hip-hop artist, whose iconic rhymes and charismatic stage presence will bring the festival to a thrilling close.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="danny-howe.jpg" alt="&copy; Danny Howe" />
  </div>
  <div class="paragraph">
    <p>On the second stage, indie bands and singer-songwriters showcase their unique styles and sounds. The performers on this stage are often the most buzzed-about acts of the festival, with a loyal and passionate following. From dreamy shoegaze bands to alternative rock acts, the second stage offers a more intimate and personal experience for music lovers looking to discover new artists.</p>
    <p>The third stage is dedicated to up-and-coming artists from different genres, providing a platform for emerging talent to showcase their skills and gain exposure. This stage is a great opportunity for attendees to discover new artists and support the next generation of musicians.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="krists-luhaers.jpg" alt="&copy; Krists Luhaers" />
  </div>
  <div class="paragraph">
    <p>Throughout the festival, DJs and electronic acts keep the energy up between sets, playing a mix of classic and contemporary dance tracks that will keep the crowd moving and grooving.</p>
    <p>Overall, the music festival offers a diverse and exciting lineup that caters to different tastes and styles. From established headliners to emerging talent, the festival promises a memorable and thrilling musical experience for all attendees.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="tijs-van-leur.jpg" alt="&copy; Tijs Van Leur" />
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
  }
  @media screen and (min-width: 820px) and (max-width: 1439px) {
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
  }
</style>
