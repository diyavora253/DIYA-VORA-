
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Diya Vora | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #0f172a;
  color: white;
}

/* Navbar */
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 10%;
  background: #020617;
}

nav h1 {
  color: #38bdf8;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 20px;
}

nav a:hover {
  color: #38bdf8;
}

/* Hero */
.hero {
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 40px;
}

.hero span {
  color: #38bdf8;
}

.hero p {
  margin-top: 10px;
  color: #94a3b8;
}

.btn {
  margin-top: 20px;
  display: inline-block;
  padding: 10px 20px;
  background: #38bdf8;
  color: black;
  border-radius: 5px;
  text-decoration: none;
}

/* Sections */
section {
  padding: 60px 10%;
}

h2 {
  margin-bottom: 20px;
  color: #38bdf8;
}

/* Skills */
.skills-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.skill-box {
  background: #1e293b;
  padding: 20px;
  border-radius: 10px;
  transition: 0.3s;
}

.skill-box:hover {
  transform: translateY(-5px);
}

.skill-box h3 {
  margin-bottom: 10px;
}

.skill-box span {
  display: inline-block;
  background: #0f172a;
  padding: 8px 10px;
  margin: 5px;
  border-radius: 5px;
  font-size: 14px;
}

/* Projects */
.projects {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: #1e293b;
  padding: 20px;
  border-radius: 10px;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

/* Contact */
.contact p {
  margin: 10px 0;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background: #020617;
  margin-top: 20px;
}
</style>
</head>

<body>

<!-- Navbar -->
<nav>
  <h1>Diya Vora</h1>
  <div>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- Hero -->
<div class="hero">
  <h2>Hi, I'm <span>Diya Vora</span></h2>
  <p>Aspiring <strong>AI & ML Developer</strong> | Python Programmer | Data Analyst</p>
  <a href="#projects" class="btn">View My Work</a>
</div>

<!-- About -->
<section id="about">
  <h2>About Me</h2>
  <p>
    I am <strong>Diya Vora</strong>, a passionate <strong>AI & ML enthusiast and Python developer</strong> currently pursuing B.Tech in Information Technology (6th Semester).  
    I love transforming data into meaningful insights and building intelligent applications. Skilled in <strong>Python, Machine Learning, Data Analysis, and Web Development</strong>, I aspire to create innovative solutions that leverage AI to solve real-world problems.
  </p>
</section>

<!-- Skills -->
<section id="skills">
  <h2>Skills</h2>

  <div class="skills-container">

    <div class="skill-box">
      <h3>💻 Programming</h3>
      <span>Python ⭐</span>
      <span>JavaScript</span>
      <span>PHP</span>
      <span>HTML</span>
      <span>CSS</span>
    </div>

    <div class="skill-box">
      <h3>🤖 AI / ML</h3>
      <span>Machine Learning</span>
      <span>Data Preprocessing</span>
      <span>NumPy</span>
      <span>Pandas</span>
      <span>Scikit-learn</span>
    </div>

    <div class="skill-box">
      <h3>📊 Data Analysis</h3>
      <span>Data Cleaning</span>
      <span>Data Visualization</span>
      <span>Pandas</span>
      <span>Matplotlib</span>
      <span>Excel</span>
    </div>

    <div class="skill-box">
      <h3>🌐 Web Development</h3>
      <span>Frontend Development</span>
      <span>Responsive Design</span>
      <span>PHP Backend</span>
      <span>MySQL</span>
      <span>CRUD Operations</span>
    </div>

    <div class="skill-box">
      <h3>⚙️ Tools</h3>
      <span>Git & GitHub</span>
      <span>VS Code</span>
      <span>XAMPP</span>
      <span>Jupyter Notebook</span>
    </div>

  </div>
</section>

<!-- Projects -->
<section id="projects">
  <h2>Projects</h2>
  <div class="projects">

    <div class="card">
      <h3>E-commerce Website</h3>
      <p>Developed using PHP and MySQL with full CRUD operations.</p>
    </div>

    <div class="card">
      <h3>Memory Matching Game</h3>
      <p>Interactive game built using JavaScript.</p>
    </div>

    <div class="card">
      <h3>AI/ML Projects</h3>
      <p>Currently working on AI & Data Analysis projects using Python.</p>
    </div>

  </div>
</section>

<!-- Contact -->
<section id="contact">
  <h2>Contact</h2>
  <div class="contact">
    <p>Email: diyavora253@gmail.com</p>
  </div>
</section>

<!-- Footer -->
<footer>
  <p>© 2026 Diya Vora | Portfolio</p>
</footer>

</body>
</html>
