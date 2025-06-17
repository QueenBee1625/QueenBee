<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>QueenBee Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0; padding: 0;
      background: #000;
      color: #FFD700;
    }
    header {
      background-color: #FFD700;
      color: #000;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: #000;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: #111;
      padding: 20px;
      border-radius: 8px;
    }
    h1, h2 {
      margin-bottom: 10px;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fill,minmax(250px,1fr));
      gap: 20px;
    }
    .project {
      border: 1px solid #FFD700;
      border-radius: 6px;
      overflow: hidden;
      background: #222;
    }
    .project img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .project-details {
      padding: 15px;
    }
    footer {
      text-align: center;
      margin: 40px 0;
      font-size: 0.9em;
      color: #999;
    }
  </style>
</head>
<body>
  <header>
    <h1>QueenBee</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Work</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container" id="about">
    <h2>About Me</h2>
    <p>I’m a creative freelancer who enjoys turning ideas into reality through design and independent work.</p>
  </div>

  <div class="container" id="projects">
    <h2>My Work</h2>
    <div class="projects">
      <div class="project">
        <img src="https://via.placeholder.com/300x150" alt="Poster" />
        <div class="project-details">
          <h3>Digital Poster</h3>
          <p>A creative digital poster made using Canva.</p>
        </div>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300x150" alt="Branding" />
        <div class="project-details">
          <h3>Freelance Branding</h3>
          <p>Minimal branding for a small business.</p>
        </div>
      </div>
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

