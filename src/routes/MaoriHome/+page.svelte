<script>
  import Header from "$lib/MaoriHeader.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<main>
  <div class="container-img">
    <img class="card-img" src="aditya-chinchure.jpg" alt="festival 1" caption="Aditya Chinchure" />
  </div>
  <div class="paragraph">
    <p>Nau mai ki te tino wheako hakari waiata! Whakaritea mo te ra ki tonu i nga puoro ora, nga kai pai, me nga maharatanga e kore e warewarehia.</p>
    <p>Kei roto i ta maatau hakari te tini kanorau o nga kaiwaiata mohio mai i nga momo momo, ka tino makona nga reka katoa o te puoro. Ma te maha o nga waahanga kua whakaritea puta noa i te waahi, ka taea e koe te neke mai i tetahi mahi ki tera mahi, ka kitea nga mea pai hou me te pai ki nga mahi rongonui.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="danny-howe-2.jpg" alt="festival 2" caption="Danny Howe" />
  </div>
  <div class="paragraph">
    <p>Mai i nga kaitoi e haere ake nei ki nga rangatira rangatira, kua whakaritea e matou he rarangi whakaihiihi hei pupuri i a koe ki te kanikani me te waiata puta noa i te ra. Ko ta matou hakari te waahi tino pai ki te kite i nga puoro hou, te kite i o kaitoi tino pai ki te ora, me te maumahara ki nga hoa me te whanau.</p>
    <p>Engari ko te waiata he timatanga noa iho. Ka whakanuia ano e ta maatau hakari te kowhiringa whakamiharo o nga kaihoko kai, e tuku ana i nga mea katoa mai i nga utu hakari matarohia ki etahi atu whiringa kai. E kore koe e hiakai me nga kai reka me nga inu whakamaarama e waatea ana puta noa i te waahi.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="hanny-naibaho.jpg" alt="festival 3" caption="Hanny Naibaho" />
  </div>
  <div class="paragraph">
    <p>I tua atu i te waiata me te kai, kei roto i ta maatau hakari nga momo mahi hei whakangahau i a koe puta noa i te ra. Mai i nga whakaurunga toi tae noa ki nga whare hokohoko, he mea pai mo te katoa. Ka taea e koe te hopu i nga maharatanga me o maatau whare whakaahua huihuinga me te hopu i te whaiaro me o kaitoi tino pai.</p>
    <p>No reira kaua koe e ngaro i tenei wheako hakari waiata kotahi-o-a-ahua. Tikina o tikiti inaianei ka uru mai ki a matou mo te ra waiata, ngahau me te hapori. Kare e taea e matou te tatari kia kite koe i reira!</p>
  </div>
  <div class="container-ticket">
    <p>Tikiti</p>
    <ul class="card-ticket">
      <li>Ko nga tikiti katoa he $200 mo ia tangata</li>
      <li>Me 15 tau neke atu ranei te pakeke o te hunga haere hakari</li>
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
