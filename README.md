<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Eklipse Education</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #e8eae6;
    }
    nav {
      background-color: #c4d9e6;
      padding: 10px;
      text-align: center;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    nav ul li {
      display: inline-block;
      margin: 0 15px;
    }
    nav ul li a {
      text-decoration: none;
      color: navy;
      font-weight: bold;
    }
    .hero {
      background: url("https://i.imgur.com/1Q9Z1Zm.jpeg") center/cover no-repeat;
      text-align: center;
      color: #f4b63d;
      padding: 100px 20px 40px;
    }
    .hero p {
      color: white;
      font-size: 1.2em;
    }
    .mission-vision {
      display: flex;
      justify-content: space-around;
      padding: 40px;
      background-color: #5d8c88;
      flex-wrap: wrap;
    }
    .card {
      width: 40%;
      background-color: #f8f0e3;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      margin: 10px;
    }
    .card img {
      width: 100%;
      border-radius: 50%;
      max-width: 250px;
    }
    .pillars {
      display: flex;
      justify-content: space-around;
      background-color: #e2e5de;
      padding: 40px 0;
      flex-wrap: wrap;
    }
    .pillar {
      text-align: center;
      margin: 10px;
    }
    .pillar img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 5px;
    }
    .pillar button {
      margin-top: 10px;
      padding: 10px 20px;
      font-weight: bold;
      color: darkblue;
    }
    .gallery {
      background-color: #5d8c88;
      padding: 40px 20px;
      text-align: center;
    }
    .gallery h2 {
      color: white;
    }
    .carousel {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
      flex-wrap: wrap;
    }
    .carousel img {
      border-radius: 50%;
      width: 180px;
      height: 180px;
      object-fit: cover;
    }
  </style>
</head>
<body>

  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Stories</a></li>
      <li><a href="#">HHEP</a></li>
      <li><a href="#">Branches</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">Blogs</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <div class="hero">
    <h1>Eklipse Education</h1>
    <p>Building ladders for future leaders</p>
  </div>

  <section class="mission-vision">
    <div class="card">
      <img src="https://i.imgur.com/3d70tLs.jpeg" alt="Mission" />
      <h2>Mission</h2>
      <p>
        The name "Eklipse" signifies the uncommon and remarkable potential within each child...
      </p>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/Hp1BpHR.jpeg" alt="Vision" />
      <h2>Vision</h2>
      <p>
        On July 10, Isha began her journey at Manav Seva, a community center...
      </p>
    </div>
  </section>

  <section class="pillars">
    <div class="pillar">
      <img src="https://i.imgur.com/r6w1U09.jpeg" alt="Hope" />
      <button>Hope</button>
    </div>
    <div class="pillar">
      <img src="https://i.imgur.com/ZgrB5iF.jpeg" alt="Hygiene" />
      <button>Hygiene</button>
    </div>
    <div class="pillar">
      <img src="https://i.imgur.com/yxCynPG.jpeg" alt="Education" />
      <button>Education</button>
    </div>
    <div class="pillar">
      <img src="https://i.imgur.com/A7xAOPM.jpeg" alt="Recreation" />
      <button>Recreation</button>
    </div>
  </section>

  <section class="gallery">
    <h2>Gallery</h2>
    <div class="carousel">
      <img src="https://i.imgur.com/NoAxO6Y.jpeg" alt="Gallery1" />
      <img src="https://i.imgur.com/8uKhKHZ.jpeg" alt="Gallery2" />
      <img src="https://i.imgur.com/YuxV4Vt.jpeg" alt="Gallery3" />
    </div>
  </section>

</body>
</html>
