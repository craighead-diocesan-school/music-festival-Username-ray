<body>
  <div class="flexbox_header">
    <header class="title">
      <nav>
        <div class="flexitem_header">
          <div class="flexitem_nav_1">
            <a href="/MaoriActs">Nga Mahi</a>
          </div>
        </div>
      </nav>
      <div class="flexitem_header">
        <div class="title_body">
          <h1>Huihuinga Sunburst</h1>
        </div>
      </div>
      <nav>
        <div class="flexitem_header">
          <div class="flexbox_nav">
            <div class="flexitem_nav_2"><a href="/MaoriAccommodation">Nohonga</a></div>
            <div class="flexitem_nav_2"><a href="/">Maori - Eng</a></div>
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
    margin: 5px 5px 5px 5px;
  }
  .title {
    color: #fc9145;
    font-size: 87px;
    padding: 30px 5px 20px 5px;
  }
  h1 {
    filter: drop-shadow(4px 3px 3px #000000);
    text-align: center;
    transform: translate(0, 10%);
  }
  .title_body {
    min-width: 800px;
    white-space: nowrap;
  }
  nav {
    font-size: 24px;
    filter: drop-shadow(0px 4px 4px #000000);
  }
  .flexbox_nav {
    display: flex;
    flex-direction: column;
  }
  .flexitem_nav_1 {
    background: #fc9145;
    margin: 10px;
    padding: 15px 10px 15px 10px;
    transform: translate(0, 50%);
    min-width: 225px;
    border-radius: 30px;
  }
  .flexitem_nav_2 {
    background: #fc9145;
    margin: 10px 10px 15px 10px;
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
</style>
