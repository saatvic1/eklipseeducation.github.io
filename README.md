<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Eklipse Education</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #e6f2f8;
      color: #000b4f;
    }
    nav {
      background-color: #c2e0ec;
      padding: 1em;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2em;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      text-decoration: none;
      color: #000b4f;
      font-weight: bold;
      font-size: 18px;
    }
    section {
      padding: 4em 2em;
      text-align: center;
    }
    .dark {
      background-color: #000b4f;
      color: white;
    }
    h1, h2 {
      margin-top: 0;
    }
    .highlight {
      color: #f8c033;
    }
    .about-image, .board-img, .hher-img, .branch-img, .blog-img {
      max-width: 100%;
      height: auto;
    }
    .board {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2em;
    }
    .board > div {
      max-width: 300px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2em;
      margin-top: 2em;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#stories">Stories</a>
    <a href="#hher">HHER</a>
    <a href="#branches">Branches</a>
    <a href="#projects">Projects</a>
    <a href="#blogs">Blogs</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="dark">
    <h1>Welcome to Eklipse Education</h1>
    <p>Empowering Children Through Compassion, Hygiene, and Education</p>
  </section>

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

<!-- Stories Section -->
<section id="stories">
  <div class="section-header">
    <h2>Our Stories</h2>
    <p>Real experiences, real change.</p>
  </div>
  <div class="story-cards">
    <div class="card">
      <img src="images/story1.jpg" alt="Story 1">
      <h3>A New Beginning</h3>
      <p>Through Eklipse, Aarav got his first pair of shoes and began school.</p>
    </div>
    <div class="card">
      <img src="images/story2.jpg" alt="Story 2">
      <h3>Voices of Hope</h3>
      <p>Young girls in Gujarat use art to express dreams for the future.</p>
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
