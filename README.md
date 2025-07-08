<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Eklipse Education</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      scroll-behavior: smooth;
    }
    nav {
      background-color: #c4d9e6;
      padding: 10px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 999;
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
    section {
      padding: 60px 20px;
    }
    .mission-vision {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      background-color: #5d8c88;
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
      flex-wrap: wrap;
    }
    .pillar {
      text-align: center;
      margin: 20px;
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
      text-align: center;
    }
    .gallery h2 {
      color: white;
    }
    .carousel {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .carousel img {
      border-radius: 50%;
      width: 180px;
      height: 180px;
      object-fit: cover;
    }

    /* About Section */
    #about {
      background-color: #0e1056;
      color: #f1e6b2;
      text-align: center;
    }
    #about img.hero-img {
      max-width: 80%;
      border-radius: 8px;
      margin-bottom: 30px;
    }
    .our-story {
      max-width: 800px;
      margin: auto;
      padding: 20px;
      color: white;
    }
    .board {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 40px;
    }
    .member {
      width: 300px;
      margin: 20px;
    }
    .member img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 6px;
    }
    .member h3 {
      margin: 10px 0 5px;
      font-size: 1.1em;
      color: #ffe384;
    }
    .member p {
      font-size: 0.95em;
      color: #eee;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#">Stories</a></li>
      <li><a href="#">HHEP</a></li>
      <li><a href="#">Branches</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">Blogs</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <!-- Home Section -->
  <div class="hero" id="home">
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

  <!-- About Section -->
  <section id="about">
    <h1>About Us</h1>
    <p class="subtitle">Finding Inspiration in Every Turn</p>
    <img class="hero-img" src="https://i.imgur.com/NoAxO6Y.jpeg" alt="About photo" />
    <div class="our-story">
      <h2 style="color:#ffe384;">Our Story</h2>
      <p>
        My trip to India, with its initial immersion in luxury resorts followed by a stark shift
        to the realities of underserved communities, sparked a profound sense of gratitude...
      </p>
    </div>

    <h2 style="color:#ffe384;">Meet the Board</h2>
    <div class="board">
      <div class="member">
        <img src="https://i.imgur.com/ZC4NnPY.jpeg" alt="Isha" />
        <h3>Isha Popat: Founder, CEO</h3>
        <p>
          Hi, I’m Isha, the founder of Eklipse — a mission-driven initiative born from...
        </p>
      </div>
      <div class="member">
        <img src="https://i.imgur.com/pMXgkC5.jpeg" alt="Dominique" />
        <h3>Dominique Chevalier: Director of Curriculum Development</h3>
        <p>
          Student at Lycée International School in France.
        </p>
      </div>
      <div class="member">
        <img src="https://i.imgur.com/TP4wP8U.jpeg" alt="Saatvic" />
        <h3>Saatvic Mahesh: Director of Web and Design</h3>
        <p>
          My name is Saatvic Mahesh, and I am a rising sophomore at Del Norte High School...
        </p>
      </div>
    </div>
  </section>

</body>
</html>
