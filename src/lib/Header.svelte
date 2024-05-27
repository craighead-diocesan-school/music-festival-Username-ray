<body>
  <div class="flexbox_header">
    <header class="title">
      <nav>
        <div class="flexitem_header">
          <div class="flexitem_nav_1">
            <a href="/EnglishActs">Acts</a>
          </div>
        </div>
      </nav>
      <div class="flexitem_header">
        <div class="title-body">
          <h1>Sunburst Festival</h1>
        </div>
      </div>
      <nav>
        <div class="flexbox_nav">
          <div class="flexitem_header">
            <div class="flexitem_nav_2"><a href="/EnglishAccomodation">Accomodation</a></div>
            <div class="flexitem_nav_2"><a href="/MaoriHome">Eng - Maori</a></div>
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
  }
  header {
    background-color: #a0e1fd;
    display: flex;
  }
  .title {
    color: #fc9145;
    font-size: 96px;
    padding: 30px 60px 20px 60px;
    margin: 15px;
    filter: drop-shadow(4px 3px 3px #000000);
  }
  nav {
    font-size: 24px;
    filter: drop-shadow(0px 4px 4px #000000);
  }
  .flexbox_nav {
    padding: 20px 25px 20px 25px;
    display: flex;
    flex-direction: column;
  }
  .flexitem_nav_1 {
    background: #fc9145;
    color: #000000;
    margin: 10px;
    padding: 10px;
    transform: translate(0, 50%);
  }
  .flexitem_nav_2 {
    background: #fc9145;
    color: #000000;
    margin: 10px;
    padding: 10px;
    transform: translate(0, -50%);
  }

  .flexbox_header {
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
</style>
