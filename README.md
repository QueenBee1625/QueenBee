<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>QueenBee Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: #fff;
      color: #333;
      margin: 0; padding: 0;
      overflow-x: hidden;
    }
    header {
      position: fixed;
      top: 0; left: 0; right: 0;
      background: rgba(255,255,255,0.9);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      z-index: 100;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    header .logo {
      font-size: 1.5rem;
      font-weight: 700;
      color: #333;
    }
    nav a {
      margin-left: 1.5rem;
      text-decoration: none;
      color: #333;
      font-weight: 500;
      transition: color .3s;
    }
    nav a:hover {
      color: #f9a825;
    }
    .hero {
      height: 100vh;
      background: url('C:\Users\Hp\Downloads\Screenshot 2025-05-24 081503.jpg') center/cover no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      padding-top: 60px;
    }
    .hero::after {
      content: '';
      position: absolute;
      bottom: 0; left: 0; right: 0;
      height: 150px;
      background: linear-gradient(to bottom, rgba(255,255,255,0), #fff);
    }
    .hero .intro {
      z-index: 1;
      text-align: center;
      color: white;
      max-width: 800px;
    }
    .hero h1 {
      font-size: 3rem;
      line-height: 1.2;
    }
    .hero p {
      margin-top: .8rem;
      font-size: 1.2rem;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    section h2 {
      font-size: 2rem;
      color: #333;
      margin-bottom: 1rem;
    }
    .projects, .services {
      display: grid;
      grid-template-columns: repeat(auto-fill,minmax(300px,1fr));
      gap: 2rem;
    }
    .card {
      background: #f9f9f9;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      transition: transform .3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-content {
      padding: 1rem;
    }
    .card-content h3 {
      margin: 0;
      font-weight: 600;
    }
    .card-content p {
      margin-top: .8rem;
      color: #666;
    }
    .btn {
      display: inline-block;
      padding: .8rem 1.5rem;
      background: #f9a825;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 1rem;
      font-weight: 500;
    }
    .btn:hover {
      background: #c17900;
    }
    form {
      display: grid;
      gap: 1rem;
    }
    input, textarea {
      padding: .8rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      width: 100%;
    }
    button {
      padding: .8rem;
      border: none;
      background: #f9a825;
      color: #fff;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #f9f9f9;
      color: #666;
      font-size: .9rem;
    }
    @media (max-width: 768px) {
      .hero h1 { font-size: 2.2rem; }
      .hero p { font-size: 1rem; }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">QueenBee</div>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <div class="intro">
      <h1>Hi, I’m QueenBee.</h1>
      <p>A freelance creative turning ideas into engaging digital experiences and visuals.</p>
      <a href="#projects" class="btn">See My Work</a>
    </div>
  </div>

  <section id="about">
    <h2>About Me</h2>
    <p>YOUR STORY HERE – Briefly explain your background, skills, approach, and passions.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <img src="PROJECT_IMAGE_1.jpg" alt="Project 1">
        <div class="card-content">
          <h3>Project Title 1</h3>
          <p>Short description. Replace this with your own project details.</p>
        </div>
      </div>
      <!-- Add more .card elements as needed -->
    </div>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="services">
      <div class="card">
        <h3>Service 1</h3>
        <p>Describe one of your freelance services (e.g., Illustration, Web Design).</p>
      </div>
      <!-- Add more services cards -->
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 QueenBee. All rights reserved.
  </footer>
</body>
</html>

