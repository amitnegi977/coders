<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
  <style>
    /* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #000000;
  background-color: #f4f4f4;
}

header {
  background-color: #ffffff;
  padding: 1rem;
}

header nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
}

header nav ul li {
  margin: 0 15px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

#hero {
  background: url('hero-bg.jpg') no-repeat center center/cover;
  color: rgb(0, 0, 0);
  text-align: center;
  padding: 100px 20px;
}

#hero h1 {
  font-size: 3rem;
}

#about, #projects, #contact {
  padding: 50px 20px;
  text-align: center;
}

h2 {
  margin-bottom: 20px;
  font-size: 2.5rem;
}

.projects-container {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.project-card {
  background: white;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  width: 250px;
}

.project-card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  margin-bottom: 10px;
}

#contact form {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 500px;
  margin: 0 auto;
}

#contact label {
  margin: 10px 0 5px;
}

#contact input, #contact textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
}

button {
  background-color: #333;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}

button:hover {
  background-color: #555;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
  position: fixed;
  bottom: 0;
  width: 100%;
}

  </style>
</head>
<body>

  <!-- Navigation -->
  <header>
    <nav>
        <div class="left">Amit's Portfolio</div>
        <div class="right">
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Servies</li>
                <li>Projects</li>
                <li>Contact Me</li>
            </ul>
        </div>
    </nav>
</header>

  <!-- Hero Section -->
  <section id="hero">
    <div class="hero-content">
      <h1>Hi, I'm [Amit negi]</h1>
      <p>I'm a <div>Frontend developer</div>. Welcome to my portfolio!</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello everyone My name is Amit negi 
      proffesionally i am frontend developer ,currently i search companies for internship and i am complete my basic knowledge in javascript, css, html, react.js, venu.js.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects-container">
      <!-- Project 1 -->
      <div class="project-card">
        <img src="project1.jpg" alt="Project 1">
        <h3>Project 1</h3>
        <p>A brief description of this project.</p>
        <a href="" target="_blank">View Project</a>
      </div>

      <!-- Project 2 -->
      <div class="project-card">
        <img src="gaming.route" alt="Project 2">
        <h3>Project 2</h3>
        <p>A brief description of this project.</p>
        <a href="https://amitnegi977.github.io/code/">View Project</a>
      </div>
      
      <!-- Add more projects as needed -->
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form action="your-form-handler.php" method="POST">
      <label for="name">Your Name</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Your Email</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Your Message</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 [Your Name]. All Rights Reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
# coders
presentaion
