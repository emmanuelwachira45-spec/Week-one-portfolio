# Week-one-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Emmanuel Wachira | Portfolio</title>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #0a0a0a;
  color: #eee;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 1rem;
  border-bottom: 1px solid #222;
}

nav a {
  margin: 0 10px;
  color: #aaa;
  text-decoration: none;
}

nav a:hover {
  color: #fff;
}

section {
  padding: 2rem;
  border-bottom: 1px solid #222;
}

h1, h2 {
  color: #fff;
}

.project {
  margin-bottom: 1rem;
}

form input,
form textarea,
form select {
  width: 100%;
  padding: 8px;
  margin: 5px 0;
}

button {
  padding: 10px;
  background: #c8f060;
  border: none;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 1rem;
  border-top: 1px solid #222;
  color: #777;
}
</style>
</head>

<body>

<header>
  <h1>Emmanuel Wachira</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home">
  <h2>Welcome</h2>
  <p>I am a full-stack developer passionate about building simple and responsive web applications.</p>
</section>

<section id="about">
  <h2>About Me</h2>
  <p>I am currently studying web development at IYF Weekend Academy.</p>

  <h3>Skills</h3>
  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
  </ul>
</section>

<section id="projects">
  <h2>Projects</h2>

  <div class="project">
    <h3>Portfolio Website</h3>
    <p>A personal portfolio built with HTML and CSS.</p>
  </div>

  <div class="project">
    <h3>Task Manager App</h3>
    <p>A simple to-do app using JavaScript.</p>
  </div>

  <div class="project">
    <h3>Landing Page</h3>
    <p>A responsive landing page design.</p>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>

  <form>
    <label>Full Name</label>
    <input type="text" required>

    <label>Email</label>
    <input type="email" required>

    <label>Phone</label>
    <input type="tel">

    <label>Subject</label>
    <select>
      <option>General</option>
      <option>Project</option>
      <option>Collaboration</option>
    </select>

    <label>Message</label>
    <textarea minlength="50" required></textarea>

    <label>
      <input type="checkbox"> Subscribe
    </label>

    <br><br>
    <button type="submit">Send</button>
  </form>

  <p>Email: 
    <a href="mailto:emmanuelwachira45@gmail.com">
      emmanuelwachira45@gmail.com
    </a>
  </p>
</section>

<footer>
  <p>© 2026 Emmanuel Wachira</p>
</footer>

</body>
</html>