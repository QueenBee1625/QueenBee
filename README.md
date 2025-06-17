<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>QueenBee | Freelancer</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet" />
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Roboto', sans-serif;
      background: #000;
      color: #fff;
    }
    header {
      background: #000;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      color: #FFD700;
      font-size: 2.5rem;
    }
    nav {
      background: #111;
      text-align: center;
      padding: 0.5rem;
    }
    nav a {
      color: #FFD700;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      height: 100vh;
      background: url('queenbee-banner.jpg') center/cover no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      text-align: center;
    }
    .hero::after {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.6);
      z-index: 0;
    }
    .hero-content {
      position: relative;
      z-index: 1;
    }
    .hero h1 {
      font-size: 3rem;
      color: #FFD700;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.5rem;
      color: #fff;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      background: #111;
      padding: 20px;
      border-radius: 8px;
    }

    h2 {
      color: #FFD700;
      margin-bottom: 10px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 8px;
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    .button {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: #FFD700;
      color: black;
      font-weight: bold;
      text-decoration: none;
      border-radius: 30px;
      transition: background 0.3s, transform 0.2s;
    }

    .button:hover {
      background: #e6c200;
      transform: scale(1.1);
    }

    footer {
      text-align: center;
      margin: 40px 0;
      font-size: 0.9em;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>QueenBee</h1>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <div class="hero-content">
      <h1>Hello, I'm QueenBee</h1>
      <p>Creative Freelancer | Visual Thinker | Dream Builder</p>
      <a class="button" href="#contact">Hire Me</a>
    </div>
  </section>

  <div class="container" id="about">
    <h2>About Me</h2>
    <p>I bring ideas to life with passion and creativity. Whether it's visuals, branding, or digital design, I work independently and strive to create impact through thoughtful design and storytelling.</p>
  </div>

  <div class="container" id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="work1.jpg" alt="Work 1" />
      <img src="work2.jpg" alt="Work 2" />
      <img src="work3.jpg" alt="Work 3" />
      <img src="work4.jpg" alt="Work 4" />
    </div>
  </div>

  <div class="container" id="contact">
    <h2>Contact</h2>
    <p>Email: queenbeefreelancing@gmail.com</p>
  </div>

  <footer>
    &copy; 2025 QueenBee. All rights reserved.
  </footer>
</body>
</html>


