<script>
  import Header from "$lib/EnglishHeader.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<Header />

<main>
  <ul class="hoge-list">
    <li class="hoge-item">
      <img class="hoge-item-image" src="samuel-regan-asante.jpg" alt="festival 4" caption="Samuel Regan Asante" />
    </li>
    <li class="hoge-item">
      <img class="hoge-item-image" src="colin-lloyd-2.jpg" alt="festival 5" caption="Collin Lloyd" />
    </li>
    <li class="hoge-item">
      <img class="hoge-item-image" src="colin-lloyd.jpg" alt="festival 6" caption="Collin Lloyd" />
    </li>
    <li class="hoge-item">
      <img class="hoge-item-image" src="maxwell-collins.jpg" alt="festival 7" caption="Maxwell Collins" />
    </li>
  </ul>
  <div class="paragraph">
    <p>Experience the ultimate music festival adventure with our tent accommodation packages! With our comfortable and convenient tents, you can immerse yourself in the festival atmosphere and stay close to all the action.</p>
    <p>Our tents are spacious and come equipped with everything you need for a comfortable stay. With comfortable beds, pillows, and blankets, you can get a good night's sleep and wake up feeling refreshed and ready for another day of music and fun.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="james-genchi.jpg" alt="festival 8" caption="Danny Genchi" />
  </div>
  <div class="paragraph">
    <p>Located within the festival grounds, our tents are just a short walk away from all the stages and attractions. You won't have to worry about transportation or navigating crowds to get to the festival – you'll be right in the heart of it all.</p>
    <p>Our tents also come with a range of amenities to make your stay even more comfortable. You'll have access to clean restroom facilities, hot showers, and charging stations for your devices. We also have a dedicated staff available to assist with any needs or questions you may have during your stay.</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="jade-masri.jpg" alt="festival 9" caption="Jade Masri" />
  </div>
  <div class="paragraph">
    <p>But the best part of our tent accommodation packages is the community. You'll be surrounded by other festival-goers who are just as excited as you are to be a part of the experience. You'll make new friends, share stories, and create memories that will last a lifetime.</p>
    <p>Don't miss out on this opportunity to enhance your music festival experience. Book your tent accommodation package today and get ready for an unforgettable adventure. We can't wait to see you there!</p>
  </div>
  <div class="container-img">
    <img class="card-img" src="tony-pham.jpg" alt="festival 10" caption="Tony Pham" />
  </div>
  <div class="container-tent">
    <p>Tent sites</p>
    <ul class="card-tent">
      <li>Tent sites are $15 per night</li>
      <li>OR</li>
      <li>$40 with a tent included</li>
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
    .container-tent {
      filter: drop-shadow(2.6px 2.6px 2.6px #000000);
      width: 161.8px;
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
    .container-tent {
      filter: drop-shadow(5.5px 5.5px 5.5px #000000);
      width: 341.7px;
    }
  }
</style>
