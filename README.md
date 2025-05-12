<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    :root {
      --primary-color: #2c3e50;
      --accent-color: #3498db;
      --background-color: #f9f9f9;
      --text-color: #333;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--background-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    header {
      background-color: var(--primary-color);
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    nav {
      background-color: #1a252f;
      padding: 1rem 0;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
    }

    nav a:hover {
      color: var(--accent-color);
    }

    main {
      max-width: 960px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      margin-bottom: 2.5rem;
    }

    section h2 {
      color: var(--primary-color);
      margin-bottom: 1rem;
    }

    footer {
      background-color: var(--primary-color);
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }

      nav a {
        display: inline-block;
        margin: 8px 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Welcome to my personal website</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        Hi! I'm Your Name, a [your role, e.g., "web developer", "designer", "student"] passionate about building fast, accessible, and user-friendly websites.
      </p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <p>
        Here are some of the projects I've worked on. Stay tuned as I update this section with links and screenshots.
      </p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>
        You can reach me at <a href="mailto:your.email@example.com">your.email@example.com</a> or follow me on 
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>.
      </p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>

 

