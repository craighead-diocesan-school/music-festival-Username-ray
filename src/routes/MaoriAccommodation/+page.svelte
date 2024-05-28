<script>
  import Header from "$lib/MaoriHeader.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<main>
  <ul class="hoge-list">
    <li class="hoge-item">
      <img class="hoge-item-image" src="samuel-regan-asante.jpg" alt="&copy; Samuel Regan Asante" />
    </li>
    <li class="hoge-item">
      <img class="hoge-item-image" src="colin-lloyd-2.jpg" alt="&copy; Collin Lloyd" />
    </li>
    <li class="hoge-item">
      <img class="hoge-item-image" src="colin-lloyd.jpg" alt="&copy; Collin Lloyd" />
    </li>
    <li class="hoge-item">
      <img class="hoge-item-image" src="maxwell-collins.jpg" alt="&copy; Maxwell Collins" />
    </li>
  </ul>
  <div class="paragraph">
    <p>Ka wheako i te tino haerenga ki te hakari waiata me o tatou kete noho teneti! Ma o matou teneti whakamarie me te watea, ka taea e koe te ruku ia koe ki roto i te ahua o te hakari me te noho tata ki nga mahi katoa.</p>
    <p>He mahorahora o matou teneti me nga mea katoa e hiahia ana koe mo te noho pai. Ma nga moenga pai, nga urunga, me nga paraikete, ka taea e koe te moe pai i te po me te oho ake me te noho rite mo tetahi atu ra waiata me te ngahau.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="james-genchi.jpg" alt="&copy; Danny Genchi" />
  </div>
  <div class="paragraph">
    <p>Kei roto i te papa hakari, he iti noa te hikoi atu o matou teneti mai i nga waahanga me nga waahi. Kare koe e manukanuka ki te kawe waka, ki te whakatere i te mano kia tae atu ki te hakari - ka noho koe ki roto i te ngakau o enei mea katoa.</p>
    <p>Ka tae mai ano o matou teneti me te maha o nga taputapu kia pai ake ai to noho. Ka whai waahi koe ki nga whare horoi horoi, nga ua wera, me nga teihana utu mo o taputapu. Kei a matou he kaimahi motuhake e waatea ana ki te awhina i nga hiahia me nga patai kei a koe i a koe e noho ana.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="jade-masri.jpg" alt="&copy; Jade Masri" />
  </div>
  <div class="paragraph">
    <p>Engari ko te mea pai rawa atu o a maatau kete noho teneti ko te hapori. Ka karapotia koe e etahi atu kaikawe hakari e rite ana ki a koe te hikaka ki te whai waahi ki te wheako. Ka whai hoa hou koe, ka tiritiri korero, ka hanga maumahara ka mau mo te wa katoa.</p>
    <p>Kaua e ngaro i tenei waahi ki te whakanui i to wheako hakari waiata. Tuhia to kete noho teneti i tenei ra, kia rite mo te haerenga e kore e warewarehia. Kare e taea e matou te tatari kia kite koe i reira!</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="tony-pham.jpg" alt="&copy; Tony Pham" />
  </div>
  <div class="container-tent">
    <p>Nga waahi teneti</p>
    <ul class="card-tent">
      <li>Ko nga waahi teneti he $15 ia po</li>
      <li>RĀNEI</li>
      <li>$40 me te teneti kei roto</li>
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
  .container-tent {
    font-family: "Playfair Display SC", serif;
    background: #fc9145;
    filter: drop-shadow(10px 10px 10px #000000);
    width: 700px;
    margin: 0 auto;
    margin-top: 10px;
  }
  .hoge-list {
    display: flex;
    flex-wrap: wrap;
    gap: 17px;
  }
  .hoge-item-image {
    filter: drop-shadow(10px 10px 10px #000000);
  }
  .hoge-item {
    width: calc(25% - 30px * 3 / 4);
    background-color: #a0e1fd;
    padding: 10px 10px 0px 10px;
    margin-top: 10px;
  }
  .hoge-item:nth-child(1n) {
    margin-left: 8px;
  }
</style>
