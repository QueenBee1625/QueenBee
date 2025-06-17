<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>QueenBee Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }

  </style>
</head>
<body>
  <header>
    <h1>QueenBee</h1>
    <p>Freelancer | Creative Thinker</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container" id="about">
    <h2>About Me</h2>
    <p>I’m QueenBee — a creative freelancer passionate about design, innovation, and turning ideas into stunning digital work.</p>
  </div>

  <div class="container" id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project">
        <img src="https://via.placeholder.com/300x150?text=Crazy+Thoughts" alt="Crazy Thoughts" />
        <div class="project-details">
          <h3>Crazy Thoughts</h3>
          <p>Creative art series exploring abstract digital expression.</p>
        </div>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300x150?text=Brand+Kit" alt="Brand Kit Design" />
        <div class="project-details">
          <h3>Brand Kit Design</h3>
          <p>Full branding and identity kit for small businesses and creators.</p>
        </div>
      </div>
    </div>
  </div>

  <div class="container" id="gallery">
    <h2>Gallery</h2>
    <div class="projects">
      <div class="project">
        <img src="https://via.placeholder.com/300x150?text=Design+1" alt="Gallery Image 1" />
        <div class="project-details">
          <h3>Illustration 1</h3>
        </div>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300x150?text=Design+2" alt="Gallery Image 2" />
        <div class="project-details">
          <h3>Poster Art</h3>
        </div>
      </div>
    </div>
  </div>

  <div class="container" id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p>Email: <a href="mailto:queenbeefreelancing@gmail.com">queenbeefreelancing@gmail.com</a></p>
    <p>Instagram: <a href="https://instagram.com/yourusername" target="_blank">@yourusername</a></p>
  </div>

  <footer>
    &copy; 2025 QueenBee. All rights reserved.
  </footer>
</body>
</html>
