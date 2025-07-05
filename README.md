# PRODIGY_WD_04
#Personal portfolio website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: lightblue;
    }

    header {
      background-color: #0d6efd;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
    }

    header p {
      margin-top: 10px;
      font-size: 1.2rem;
    }

    nav {
      background-color: #222;
      padding: 10px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 30px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #0d6efd;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .home {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 30px;
    }

    .home img {
      max-width: 250px;
      border-radius: 50%;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    .home-content {
      max-width: 500px;
    }

    .home-content h2 {
      margin-bottom: 15px;
      color: #0d6efd;
    }

    .about, .projects, .contact {
      background-color: #fff;
      margin-top: 20px;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    .projects .project {
      margin-bottom: 20px;
    }

    .projects .project h3 {
      color: #0d6efd;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    form button {
      background-color: #0d6efd;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    form button:hover {
      background-color: #0b5ed7;
    }

    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 20px 10px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .home {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Hello, I'm Sivaranjinee</h1>
    <p>Web Developer • Designer • Student</p>
  </header>

  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About Me</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="home" class="home">
    <div class="home-content">
      <h2>Frontend Web Developer</h2>
      <p>I build responsive and modern web applications using React.js, Tailwind CSS, Node.js, and MongoDB. I love transforming ideas into real-world solutions that make a difference.</p>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I'm Sivaranjinee, currently pursuing my B.Tech. in Computer Science and Business System at RMK Engineering College. I specialize in web development and am passionate about creating user-friendly, fast, and accessible web applications. I also enjoy learning new technologies and solving real-world problems through code.</p>

    <h3>Education</h3>
    <ul>
      <li><strong>B.Tech</strong> – RMK Engineering College </li>
  
    </ul>

    <h3>Experience</h3>
    <p>Currently building a project titled <strong>“Automated System for Career Advancement”</strong> using React, Node, MongoDB. I’ve also worked on mini-projects like portfolio sites, to-do apps, and a library system using Java.</p>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Automated Career Advancement System</h3>
      <p>A full-stack platform for faculty to track achievements and apply for promotions. Built with React.js, Express.js, MongoDB, and JWT authentication.</p>
    </div>
    <div class="project">
      <h3>To-Do App</h3>
      <p>Simple yet powerful task manager with filtering and local storage support.</p>
    </div>
    <div class="project">
      <h3>Library Management (Java)</h3>
      <p>Console-based system with book issue/return logic and data storage using classes.</p>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form onsubmit="alert('Thanks for reaching out!'); return false;">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Sivaranjinee • All Rights Reserved</p>
  </footer>

</body>
</html>

