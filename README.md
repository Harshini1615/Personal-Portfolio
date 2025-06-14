# Personal-Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav {
      background-color: #444;
      text-align: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    main {
      max-width: 900px;
      margin: 20px auto;
      padding: 0 20px;
      background: white;
    }

    section {
      margin-bottom: 40px;
    }

    h2 {
      color: #222;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }

    article {
      margin-bottom: 20px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px 0;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    label {
      margin-top: 10px;
      font-weight: bold;
    }

    input, textarea {
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    button {
      margin-top: 15px;
      padding: 10px;
      background-color: #333;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 4px;
    }

    button:hover {
      background-color: #555;
    }
  </style>
</head>
<body>

  <header>
    <h1>My Portfolio</h1>
    <p>Web Developer | Designer | Learner</p>
  </header>

  <nav>
    <a href="#about">About Me</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I'm a passionate web developer learning to build beautiful and functional websites. I enjoy working on new projects, learning technologies, and solving real-world problems using code.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      
      <article>
        <h3>Project One: Task Tracker</h3>
        <p>A simple web app to track your daily tasks. Built with HTML, CSS, and JavaScript. Includes features like add/edit/delete and local storage.</p>
      </article>

      <article>
        <h3>Project Two: Weather App</h3>
        <p>This app fetches real-time weather data using an API and displays it with icons and temperature. Made using HTML, CSS, and vanilla JavaScript.</p>
      </article>

      <article>
        <h3>Project Three: Personal Blog</h3>
        <p>A static blog website using semantic HTML and styled with basic CSS. It includes blog posts, author bio, and a comment section (non-functional).</p>
      </article>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>

</body>
</html>
