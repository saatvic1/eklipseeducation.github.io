<!DOCTYPE html>
<html lang="en">
  <nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#stories">Stories</a></li>
    <li><a href="#hher">HHER</a></li>
    <li><a href="#branches">Branches</a></li>
    <li><a href="#projects">Projects</a></li>
  </ul>
</nav>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Eklipse Education</title>
  <style>
    * { box-sizing: border-box; }
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

    /* --- HOME --- */
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

    /* --- ABOUT --- */
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

    /* --- STORIES --- */
    #stories {
      background-color: #2e496b;
      color: white;
    }
    #stories h1 {
      text-align: center;
      font-size: 3em;
    }
    #stories p.subtitle {
      text-align: center;
      font-size: 1.2em;
      margin-bottom: 40px;
    }
    .story-block {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      margin: 30px 0;
      padding: 30px;
      background-color: #e0eaf4;
      color: #000;
    }
    .story-block img {
      width: 45%;
      max-width: 400px;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    .story-text {
      width: 50%;
    }
    .story-text h3 {
      color: #2e496b;
      font-size: 1.4em;
    }
    .grid-stories {
      background-color: #dce9f5;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 40px;
      gap: 20px;
    }
    .grid-card {
      width: 200px;
      text-align: center;
    }
    .grid-card img {
      width: 100%;
      border-radius: 10px;
      height: 200px;
      object-fit: cover;
    }
    .grid-card h4 {
      color: #2e496b;
      margin: 10px 0 5px;
    }

    /* --- HHER --- */
    #hher {
      background-color: #dfeef4;
    }
    #hher h1 {
      text-align: center;
      color: #1d3557;
      font-size: 3em;
    }
    #hher p.subtitle {
      text-align: center;
      font-size: 1.2em;
      color: #2e496b;
    }
    .hher-box {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 40px;
      margin-bottom: 20px;
    }
    .hher-box img {
      width: 300px;
      border-radius: 10px;
    }
    .hher-box div {
      max-width: 600px;
      margin: 10px;
    }
    .hher-box h2 {
      color: #1d3557;
    }
  </style>
</head>
<body>

  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#stories">Stories</a></li>
      <li><a href="#hher">HHER</a></li>
    </ul>
  </nav>

  <div class="hero" id="home">
    <h1>Eklipse Education</h1>
    <p>Building ladders for future leaders</p>
  </div>

  <section class="mission-vision">
    <div class="card">
      <img src="https://i.imgur.com/3d70tLs.jpeg" alt="Mission" />
      <h2>Mission</h2>
      <p>The name "Eklipse" signifies the uncommon and remarkable potential within each child...</p>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/Hp1BpHR.jpeg" alt="Vision" />
      <h2>Vision</h2>
      <p>On July 10, Isha began her journey at Manav Seva, a community center...</p>
    </div>
  </section>

  <section class="pillars">
    <div class="pillar"><img src="https://i.imgur.com/r6w1U09.jpeg" alt="Hope" /><button>Hope</button></div>
    <div class="pillar"><img src="https://i.imgur.com/ZgrB5iF.jpeg" alt="Hygiene" /><button>Hygiene</button></div>
    <div class="pillar"><img src="https://i.imgur.com/yxCynPG.jpeg" alt="Education" /><button>Education</button></div>
    <div class="pillar"><img src="https://i.imgur.com/A7xAOPM.jpeg" alt="Recreation" /><button>Recreation</button></div>
  </section>

  <section class="gallery">
    <h2>Gallery</h2>
    <div class="carousel">
      <img src="https://i.imgur.com/NoAxO6Y.jpeg" />
      <img src="https://i.imgur.com/8uKhKHZ.jpeg" />
      <img src="https://i.imgur.com/YuxV4Vt.jpeg" />
    </div>
  </section>

  <section id="about">
    <h1>About Us</h1>
    <p class="subtitle">Finding Inspiration in Every Turn</p>
    <img class="hero-img" src="https://i.imgur.com/NoAxO6Y.jpeg" />
    <div class="our-story"><h2 style="color:#ffe384;">Our Story</h2><p>My trip to India... [Your full story]</p></div>
    <h2 style="color:#ffe384;">Meet the Board</h2>
    <div class="board">
      <div class="member"><img src="https://i.imgur.com/ZC4NnPY.jpeg" /><h3>Isha Popat</h3><p>Founder & CEO...</p></div>
      <div class="member"><img src="https://i.imgur.com/pMXgkC5.jpeg" /><h3>Dominique</h3><p>Curriculum Director</p></div>
      <div class="member"><img src="https://i.imgur.com/TP4wP8U.jpeg" /><h3>Saatvic Mahesh</h3><p>Director of Web</p></div>
    </div>
  </section>

  <section id="stories">
    <h1>Stories</h1>
    <p class="subtitle">Heartwarming stories of the children impacted by our efforts!</p>
    <div class="story-block"><img src="https://i.imgur.com/uq0wvIN.jpeg" /><div class="story-text"><h3>Priyansh</h3><p>Priyansh's story here...</p></div></div>
    <div class="grid-stories">
      <div class="grid-card"><img src="https://i.imgur.com/f9Wv0e2.jpeg" /><h4>Jaysheel</h4><p>...</p></div>
      <div class="grid-card"><img src="https://i.imgur.com/ZPRzXYz.jpeg" /><h4>Three Girls</h4><p>...</p></div>
      <div class="grid-card"><img src="https://i.imgur.com/mBEakg5.jpeg" /><h4>Prachi</h4><p>...</p></div>
      <div class="grid-card"><img src="https://i.imgur.com/hGQdEJg.jpeg" /><h4>Kinjal</h4><p>...</p></div>
      <div class="grid-card"><img src="https://i.imgur.com/0fA34wF.jpeg" /><h4>Riya</h4><p>...</p></div>
    </div>
    <div class="story-block" style="background:#f0f5fc;"><img src="https://i.imgur.com/NdWnDZO.jpeg" /><div class="story-text"><h3>Vihaan</h3><p>...</p></div></div>
  </section>

  <section id="hher">
    <h1>HHER</h1>
    <p class="subtitle">The driving force behind our mission!</p>
    <div class="hher-box" style="background:#f1f9ff;">
      <img src="https://i.imgur.com/2IWh58W.jpeg" /><div><h2>Hope</h2><p>...</p></div>
    </div>
    <div class="hher-box" style="background:#e4f3fb;">
      <div><h2>Hygiene</h2><p>...</p></div><img src="https://i.imgur.com/M9QJjgd.jpeg" />
    </div>
    <div class="hher-box" style="background:#f1f9ff;">
      <img src="https://i.imgur.com/mzqZxzK.jpeg" /><div><h2>Education</h2><p>...</p></div>
    </div>
    <div class="hher-box" style="background:#e4f3fb;">
      <div><h2>Recreation</h2><p>...</p></div><img src="https://i.imgur.com/gOIsC7Z.jpeg" />
    </div>
  </section>

<!-- Branches Section -->
<section id="branches" style="background-color: #e0f0f7; padding: 60px 20px;">
  <h1 style="text-align: center; color: #1d3557; font-size: 3em;">Our Growth</h1>
  <p style="text-align: center; font-size: 1.1em; max-width: 800px; margin: auto; color: #2e496b;">
    Eklipse, which began at Canyon Crest Academy, is now expanding its reach to schools throughout the city.
    We are incredibly inspired by the students who have embraced Eklipse’s mission, and together,
    we can empower children in India to truly flourish academically and access the essential resources they need.
  </p>

  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 30px; margin-top: 40px;">
    <img src="https://i.imgur.com/VsVBDMd.jpeg" alt="Canyon Crest Academy" style="width: 280px; border-radius: 10px;" />
    <img src="https://i.imgur.com/UgRPpyq.jpeg" alt="Del Norte" style="width: 280px; border-radius: 10px;" />
    <img src="https://i.imgur.com/4rgje5u.jpeg" alt="Westview" style="width: 280px; border-radius: 10px;" />
    <img src="https://i.imgur.com/gMFHxW3.jpeg" alt="Scripps Ranch" style="width: 280px; border-radius: 10px;" />
    <img src="https://i.imgur.com/D7McUjU.jpeg" alt="La Jolla Country Day" style="width: 280px; border-radius: 10px;" />
    <img src="https://i.imgur.com/gMFHxW3.jpeg" alt="Scripps Ranch Again" style="width: 280px; border-radius: 10px;" />
  </div>
</section>

<!-- Projects Section -->
<section id="projects" style="background-color: #e0f0f7; padding: 60px 20px;">
  <h1 style="text-align: center; color: #1d3557; font-size: 3em;">Our Initiatives</h1>
  <p style="text-align: center; font-size: 1.1em; max-width: 800px; margin: auto; color: #2e496b;">
    We are actively launching and supporting grassroots projects to create real impact — from education and hygiene
    to sustainable development. Stay tuned for updates on how we’re empowering children across India through
    focused, community-driven initiatives.
  </p>

  <div style="margin-top: 50px; text-align: center;">
    <img src="https://i.imgur.com/NZdS3Md.jpeg" alt="Waterfall Project Background" style="width: 90%; max-width: 800px; border-radius: 15px; box-shadow: 0px 5px 15px rgba(0,0,0,0.1);" />
  </div>
</section>
</body>
</html>
