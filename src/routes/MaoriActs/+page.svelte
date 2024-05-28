<script>
  import Header from "$lib/MaoriHeader.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<main>
  <div class="container-img">
    <img class="card-img" src="aranxa-esteve.jpg" alt="&copy; Aranxa Esteve" />
  </div>
  <div class="paragraph">
    <p>Ko te huihuinga waiata e whakanui ana i te rarangi whakaihiihi o nga kaiwaiata mohio mai i nga momo momo momo, e kii ana i te wheako kanorau me te whakangahau mo nga taangata katoa.</p>
    <p>I runga i te atamira matua, ko nga kaikorero he ranunga o nga mahi kua tau me nga mahi kakea ake, e taurangi ana ka uru mai te mano tini. Ko te upoko tuatahi he roopu toka rongonui, e mohiotia ana mo o raatau mahi kaha me nga matau hopu. Whai muri i a raatau ko tetahi kaitoi rongonui rongonui, ko ona tino pai me te hopukanga e tino kaha ana te iwi ki te kanikani me te waiata. He tohunga toi hip-hop te rangatira o te mutunga, na ona riipene rongonui me te aroaro o te atamira whakahirahira ka mutu te hakari.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="danny-howe.jpg" alt="&copy; Danny Howe" />
  </div>
  <div class="paragraph">
    <p>I te wahanga tuarua, ko nga roopu indie me nga kaiwaiata-waiata e whakaatu ana i o raatau ahua me o raatau oro. Ko nga kaihaka i runga i tenei atamira ko te nuinga o nga wa e pa ana ki nga mahi o te hakari, me te piripono me te ngakau nui ki te whai. Mai i nga roopu huu moemoea ki nga mahi toka rerekee, ko te waahanga tuarua he wheako tino pai ake, he wheako whaiaro mo te hunga e aroha ana ki te puoro e rapu ana ki te rapu tohunga toi hou.</p>
    <p>Ko te wahanga tuatoru e whakatapua ana ki nga kaitoi e haere mai ana mai i nga momo momo rereke, e whakarato ana i te papa mo nga taranata ka puta ake hei whakaatu i o raatau pukenga me te whai waahi. He waahi pai tenei wahanga mo te hunga i tae atu ki te kimi kaitoi hou me te tautoko i te reanga o nga kaiwaiata.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="krists-luhaers.jpg" alt="&copy; Krists Luhaers" />
  </div>
  <div class="paragraph">
    <p>Puta noa i te hakari, ko nga DJ me nga mahi hiko e pupuri ana i te kaha ki waenga i nga huinga, e purei ana i te ranunga o nga ara kanikani matarohia me nga waiata o naianei e pupuri ana i te marea e neke haere ana.</p>
    <p>I roto i te katoa, ko te huihuinga waiata e tuku ana i te raupapa rereke me te whakaihiihi e whakatutuki ana i nga reka me nga momo rereke. Mai i nga rangatira rangatira ki nga taranata ka puta ake, ka oati te huihuinga he wheako puoro e maumahara ana, e whakahihiri ana hoki mo te hunga katoa i tae atu.</p>
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
</style>
