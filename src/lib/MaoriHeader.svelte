<head>
  <script src="https://kit.fontawesome.com/d3985f95e2.js" crossorigin="anonymous"></script>
</head>

<body>
  <div class="flexbox_header">
    <header class="title">
      <nav>
        <div class="flexitem_header">
          <div class="flexitem_nav_1">
            <a href="/MaoriActs" class="acts"><i class="fa-solid fa-users-viewfinder"></i> Nga Mahi</a>
          </div>
        </div>
      </nav>
      <div class="flexitem_header">
        <div class="title_body">
          <h1><a class="nav_text" href="/MaoriHome">Mhuihuinga Sunburst</a></h1>
        </div>
      </div>
      <nav>
        <div class="flexitem_header">
          <div class="flexbox_nav">
            <div class="flexitem_nav_2"><a href="/MaoriAccommodation" class="accommodation"><i class="fa-solid fa-tents fa-xs"></i> Nohonga</a></div>
            <div class="flexitem_nav_2"><a href="/" class="language"><i class="fa-solid fa-globe fa-xs"></i> Maori - Eng</a></div>
          </div>
        </div>
      </nav>
    </header>
  </div>
</body>

<style>
  body {
    font-family: "Playfair Display SC", serif;
    text-align: center;
    background-color: #c4d3d4;
  }
  header {
    background-color: #a0e1fd;
    display: flex;
    margin: 5px 3px 5px 3px;
  }
  .title {
    color: #fc9145;
    font-size: 81px;
    padding: 30px 5px 20px 5px;
  }
  .nav_text {
    color: #fc9145;
  }
  h1 {
    filter: drop-shadow(4px 3px 3px #000000);
    text-align: center;
    transform: translate(0, 15%);
  }
  .title_body {
    white-space: nowrap;
  }
  nav {
    font-size: 20.5px;
    filter: drop-shadow(0px 4px 4px #000000);
  }
  .flexbox_nav {
    display: flex;
    flex-direction: column;
  }
  .flexitem_nav_1 {
    background: #fc9145;
    margin: 8px;
    padding: 15px 10px 15px 10px;
    transform: translate(0, 50%);
    min-width: 225px;
    border-radius: 30px;
  }
  .flexitem_nav_2 {
    background: #fc9145;
    margin: 10px 8px 15px 8px;
    padding: 15px 10px 15px 10px;
    min-width: 225px;
    border-radius: 30px;
  }
  a {
    color: #000000;
  }
  .flexbox_header {
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
  .flexitem_nav_1:hover {
    background-color: #000000;
  }
  .flexitem_nav_2:hover {
    background-color: #000000;
  }
  a:not(.nav_text):hover {
    color: #fc9145;
  }
  .nav_text:hover {
    color: #000000;
  }
  .acts {
    filter: drop-shadow(0px 3px 3px #3e3a39);
    font-weight: bold;
  }
  .accommodation {
    filter: drop-shadow(0px 3px 3px #3e3a39);
    font-weight: bold;
  }
  .language {
    filter: drop-shadow(0px 3px 3px #3e3a39);
    font-weight: bold;
  }
  .acts:hover {
    filter: drop-shadow(0px 3px 3px #fc9145);
  }
  .accommodation:hover {
    filter: drop-shadow(0px 3px 3px #fc9145);
  }
  .language:hover {
    filter: drop-shadow(0px 3px 3px #fc9145);
  }
  @media screen and (min-width: 390px) and (max-width: 819px) {
    header {
      margin: 1.3px 1.3px 1.3px 1.3px;
    }
    .title {
      font-size: 22.4px;
      padding: 7.7px 1.3px 5.2px 1.3px;
    }
    h1 {
      filter: drop-shadow(1px 0.8px 0.8px #000000);
      transform: translate(0, 10%);
    }
    .title_body {
      min-width: 206.3px;
    }
    nav {
      font-size: 5.6px;
      filter: drop-shadow(0px 1px 1px #000000);
    }
    .flexitem_nav_1 {
      margin: 2.06px;
      padding: 3.9px 2.6px 3.9px 2.6px;
      min-width: 58px;
      border-radius: 7.7px;
    }
    .flexitem_nav_2 {
      margin: 2.6px 2.06px 3.9px 2.06px;
      padding: 3.9px 2.6px 3.9px 2.6px;
      min-width: 58px;
      border-radius: 7.7px;
    }
  }
  @media screen and (min-width: 820px) and (max-width: 1439px) {
    header {
      margin: 2.7px 2.7px 2.7px 2.7px;
    }
    .title {
      font-size: 47.1px;
      padding: 16.2px 2.7px 10.9px 2.7px;
    }
    h1 {
      filter: drop-shadow(2.1px 1.7px 1.7px #000000);
      transform: translate(0, 10%);
    }
    .title_body {
      min-width: 433.9px;
    }
    nav {
      font-size: 11.8px;
      filter: drop-shadow(0px 2.1px 2.1px #000000);
    }
    .flexitem_nav_1 {
      margin: 4.3px;
      padding: 8.2px 5.5px 8.2px 5.5px;
      min-width: 122px;
      border-radius: 16.2px;
    }
    .flexitem_nav_2 {
      margin: 5.5px 4.3px 8.2px 4.3px;
      padding: 8.2px 5.5px 8.2px 5.5px;
      min-width: 122px;
      border-radius: 16.2px;
    }
  }
</style>
