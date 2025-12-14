<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rangeli Live News</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f4f4f4;
    }
    header {
      background: #c40000;
      color: #fff;
      padding: 15px;
      text-align: center;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 15px;
    }
    .news-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 15px;
    }
    .news-card {
      background: #fff;
      padding: 15px;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    .news-card img {
      width: 100%;
      border-radius: 5px;
    }
    .news-card h3 {
      margin: 10px 0 5px;
    }
    .news-card p {
      font-size: 14px;
      color: #333;
    }
    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
    .live {
      color: yellow;
      font-weight: bold;
      animation: blink 1s infinite;
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>
</head>
<body>  <header>
    <h1>Rangeli Live News <span class="live">LIVE</span></h1>
    <p>Latest News from Rangeli & Morang</p>
  </header>  <nav>
    <a href="#">Home</a>
    <a href="#">Local News</a>
    <a href="#">Politics</a>
    <a href="#">Crime</a>
    <a href="#">Sports</a>
