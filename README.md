<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 2rem 1rem;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      margin: 0.5rem 0;
      font-size: 1.2rem;
    }
    nav {
      background: #444;
      display: flex;
      justify-content: center;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffd700;
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .card {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>👋 Hi, I'm Your Name</h1>
    <p>Web Developer | Designer | Student</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Your Name, a passionate web developer learning to build creative and user-friendly websites. I enjoy coding, design, and exploring new technologies.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Project 1</h3>
        <p>Short description of your project goes here.</p>
      </div>
      <div class="card">
        <h3>Project 2</h3>
        <p>Short description of your project goes here.</p>
      </div>
      <div class="card">
        <h3>Project 3</h3>
        <p>Short description of your project goes here.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
    <p>LinkedIn: <a href="#">linkedin.com/in/yourprofile</a></p>
    <p>GitHub: <a href="#">github.com/yourprofile</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Your Name. All rights reserved.</p>
  </footer>
</body>
</html>
