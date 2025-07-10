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
      background-color: #eaf6f9;
      color: #000c4d;
    }
    header {
      background-color: #b4d6e6;
      padding: 20px;
      display: flex;
      justify-content: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      color: #000c4d;
      border-right: 1px solid #000c4d;
      padding-right: 15px;
    }
    nav a:last-child {
      border: none;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    .hero {
      background-color: #000c4d;
      color: #f8e9a1;
    }
    .about-section, .hher-section, .branches-section, .projects-section, .blogs-section, .contact-section {
      background-color: #eaf6f9;
    }
    h1, h2, h3 {
      color: #000c4d;
    }
    .board {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 40px;
    }
    .board-member {
      max-width: 300px;
    }
    .board-member img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .hher-grid, .branches-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 40px;
    }
    .hher-block, .branch-img {
      max-width: 400px;
    }
    .blog {
      max-width: 800px;
      margin: 0 auto 60px;
      text-align: left;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 12px;
    }
    footer {
      background-color: #b4d6e6;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
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
  </header>

  <section id="home" class="hero">
    <h1>Welcome to Eklipse Education</h1>
    <p>Empowering Youth through Education & Stories</p>
  </section>

  <section id="about" class="about-section">
    <h1>About Us</h1>
    <p>Finding Inspiration in Every Turn</p>
    <img src="about-photo.jpg" alt="About photo" width="80%" />
    <h2>Our Story</h2>
    <p>My trip to India, with its initial immersion in luxury resorts followed by a stark shift to the realities of underserved communities, sparked a profound sense of gratitude. It was the small, often overlooked things that resonated most deeply...</p>
    <h2>Meet the Board</h2>
    <div class="board">
      <div class="board-member">
        <img src="isha.jpg" alt="Isha Popat" />
        <h3>Isha Popat: Founder, CEO</h3>
        <p>Hi, I’m Isha, the founder of Eklipse...</p>
      </div>
      <div class="board-member">
        <img src="dominique.jpg" alt="Dominique Chevalier" />
        <h3>Dominique Chevalier: Director of Curriculum Development</h3>
        <p>Student at Lycée International School in France.</p>
      </div>
      <div class="board-member">
        <img src="saatvic.jpg" alt="Saatvic Mahesh" />
        <h3>Saatvic Mahesh: Director of Web and Design</h3>
        <p>My name is Saatvic Mahesh, and I am a rising sophomore at Del Norte High School...</p>
      </div>
    </div>
  </section>

  <section id="hher" class="hher-section">
    <h1>HHER</h1>
    <p>The driving force behind our mission!</p>
    <div class="hher-grid">
      <div class="hher-block">
        <img src="hope.jpg" alt="Hope" />
        <h3>Hope</h3>
        <p>At the heart of our mission is hope...</p>
      </div>
      <div class="hher-block">
        <img src="hygiene.jpg" alt="Hygiene" />
        <h3>Hygiene</h3>
        <p>We believe that everyone deserves access to clean water and safe sanitation...</p>
      </div>
      <div class="hher-block">
        <img src="education.jpg" alt="Education" />
        <h3>Education</h3>
        <p>We believe that education is the key to helping people escape poverty...</p>
      </div>
      <div class="hher-block">
        <img src="recreation.jpg" alt="Recreation" />
        <h3>Recreation</h3>
        <p>We believe that play is important for kids...</p>
      </div>
    </div>
  </section>

  <section id="branches" class="branches-section">
    <h1>Our Growth</h1>
    <p>Eklipse, which began at Canyon Crest Academy, is now expanding its reach...</p>
    <div class="branches-grid">
      <img src="cca.jpg" alt="Canyon Crest Academy" class="branch-img" />
      <img src="delnorte.jpg" alt="Del Norte High" class="branch-img" />
      <img src="westview.jpg" alt="Westview" class="branch-img" />
      <img src="scripps.jpg" alt="Scripps Ranch" class="branch-img" />
      <img src="lajolla.jpg" alt="La Jolla Country Day" class="branch-img" />
    </div>
  </section>

  <section id="projects" class="projects-section">
    <h1>Our Initiatives</h1>
    <p>Discover how we’re creating impact...</p>
    <img src="projects-bg.jpg" alt="Project background" width="100%" />
  </section>

  <section id="blogs" class="blogs-section">
    <h1>Blogs</h1>
    <div class="blog">
      <h2>From Fear to Direction: How Education Became My Everything</h2>
      <p><strong>Blog Post #2 Written By Zeynep Istanbullouglu</strong></p>
      <p>When I was younger, I thought education was something you simply had to get through...</p>
    </div>
    <div class="blog">
      <h2>Education: The Key to Breaking the Cycle of Poverty</h2>
      <p><strong>Blog Post #1 Written By Aadi Jariwala</strong></p>
      <p>Education is more than just learning to read, write, and add—it is arguably the most powerful tool...</p>
    </div>
  </section>

  <section id="contact" class="contact-section">
    <h1>Connect with us for more information</h1>
    <p>Email us at: contact@eklipse.org</p>
    <button>Contact Form</button>
  </section>

  <footer>
    <p>© 2025 Eklipse Education. All rights reserved.</p>
  </footer>
</body>
</html>
