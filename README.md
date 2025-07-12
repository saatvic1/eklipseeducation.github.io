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


  <section id="about">
    <h1>About Us</h1>
    <p>Finding Inspiration in Every Turn</p>
    <img src="about-image.jpg" alt="Children smiling" class="about-image" />
    <h2 class="highlight">Our Story</h2>
    <p>My trip to India... [Include full story text here as before]</p>
    <h2>Meet the Board</h2>
    <div class="board">
      <div>
        <img src="isha.jpg" alt="Isha" class="board-img" />
        <h3>Isha Popat: Founder, CEO</h3>
        <p>Hi, I’m Isha... [full bio]</p>
      </div>
      <div>
        <img src="dominique.jpg" alt="Dominique" class="board-img" />
        <h3>Dominique Chevalier: Director of Curriculum Development</h3>
        <p>Student at Lycée International School in France.</p>
      </div>
      <div>
        <img src="saatvic.jpg" alt="Saatvic" class="board-img" />
        <h3>Saatvic Mahesh: Director of Web and Design</h3>
        <p>My name is Saatvic... [full bio]</p>
      </div>
    </div>
  </section>

  <section id="stories" class="dark">
    <h1>Stories</h1>
    <p>Real moments that changed lives</p>
    <div class="grid">
      <div>
        <h3>Rani’s Journey</h3>
        <p>From no shoes to full-time school, Rani’s smile says it all.</p>
      </div>
      <div>
        <h3>Amit’s New World</h3>
        <p>Amit once feared math. Now he teaches it to his siblings.</p>
      </div>
      <div>
        <h3>Sunita’s Dream</h3>
        <p>Once afraid of strangers, now she leads classroom discussions.</p>
      </div>
    </div>
  </section>

  <section id="hher">
    <h1 class="highlight">HHER</h1>
    <p>The driving force behind our mission!</p>
    <div class="grid">
      <div>
        <img src="hope.jpg" alt="Hope" class="hher-img" />
        <h3>Hope</h3>
        <p>We help children build hope and confidence...</p>
      </div>
      <div>
        <img src="hygiene.jpg" alt="Hygiene" class="hher-img" />
        <h3>Hygiene</h3>
        <p>WASH education ensures healthy futures.</p>
      </div>
      <div>
        <img src="education.jpg" alt="Education" class="hher-img" />
        <h3>Education</h3>
        <p>UNESCO goals guide our learning mission.</p>
      </div>
      <div>
        <img src="recreation.jpg" alt="Recreation" class="hher-img" />
        <h3>Recreation</h3>
        <p>We bring joy and safe play into the classroom.</p>
      </div>
    </div>
  </section>

  <section id="branches" class="dark">
    <h1>Our Growth</h1>
    <p>Eklipse is expanding into schools across the city!</p>
    <div class="grid">
      <img src="cca.jpg" alt="CCA" class="branch-img" />
      <img src="del-norte.jpg" alt="Del Norte" class="branch-img" />
      <img src="westview.jpg" alt="Westview" class="branch-img" />
      <img src="scripps.jpg" alt="Scripps" class="branch-img" />
      <img src="lajolla.jpg" alt="La Jolla" class="branch-img" />
    </div>
  </section>

  <section id="projects">
    <h1 class="highlight">Our Initiatives</h1>
    <p>Discover the impact we're making on education and health.</p>
    <img src="waterfall.jpg" alt="Project background" class="project-img" />
  </section>

  <section id="blogs" class="dark">
    <h1>Blogs</h1>
    <div>
      <h2 class="highlight">From Fear to Direction: How Education Became My Everything</h2>
      <p><strong>By Zeynep Istanbulluglu</strong></p>
      <p>When I was younger... [full blog text]</p>
    </div>
    <div>
      <h2 class="highlight">Education: The Key to Breaking the Cycle of Poverty</h2>
      <p><strong>By Aadi Jariwala</strong></p>
      <p>Education is more than just learning... [full blog text]</p>
    </div>
  </section>

  <section id="contact">
    <h1 class="highlight">Get in Touch</h1>
    <h2>Connect with us for more information</h2>
    <p>Email: info@eklipse.org</p>
    <p><button>Contact Form</button></p>
  </section>

</body>
</html>

