
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
      background: #f0f0f0;
      color: #333;
    }
    header {
      background-color: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px #ccc;
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
      border: 1px solid #ddd;
      border-radius: 6px;
      overflow: hidden;
      background: #fff;
      box-shadow: 0 2px 5px rgb(0 0 0 / 0.1);
      transition: transform 0.3s;
    }
    .project:hover {
      transform: scale(1.05);
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
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>QueenBee</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container" id="about">
    <h2>About Me</h2>
    <p>Creative freelancer who loves exploring ideas and turning them into reality through independent work.</p>
  </div>

  <div class="container" id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project">
        <img src="https://![Screenshot 2025-05-24 081503](https://github.com/user-attachments/assets/aa5771d5-676e-41ea-b2f4-41e4123f49cd)
/300x150" alt="Crazy Thoughts" />
        <div class="project-details">
          <h3>Project Title 1</h3>
          <p>Short description about project 1.</p>
        </div>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300x150" alt="Project 2" />
        <div class="project-details">
          <h3>Project Title 2</h3>
          <p>Short description about project 2.</p>
        </div>
      </div>
      <!-- Add more projects as needed -->
    </div>
  </div>

  <div class="container" id="contact">
    <h2>Contact Me</h2>
    <p>Email: queenbeefreelancing@gmail.com</p>
    <!-- You can add a form here later -->
  </div>

  <footer>
    &copy; 2025 QueenBee. All rights reserved.
  </footer>
</body>
</html>

