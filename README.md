# Ex01 Portfolio
## Date:06/01/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Radhimeena  | Experiment-1</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navbar -->
  <header>
    <h1 class="logo">Prathikshaa.S</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#tech">Tech Stack</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
        <div class="hero-text">
          <div class="hero-image">
            <img src="C:\Users\admin\Downloads\WhatsApp Image 2026-02-05 at 11.17.50 AM.jpeg" alt="Profile Picture">
          </div>
        <h2>Hello all,<span>I'm Prathikshaa</span></h2>
        <p>web developer | ethical hacker </p>
        <p class="tagline">Turning ideas into production-ready full-stack applications</p>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section">
    <h2>About Me</h2>
    <p>
      As a 2nd year CSE(cyber security) student, I am an aspiring ethical hacking with hands-on experience in kali linux. I actively explore various operating system  technologies and continuously upskill myself by learning modern tools and frameworks. 
  </section>

  <!-- Skills Section -->
  <section id="skills" class="section light">
    <h2>Core Skills</h2>

    <div class="skill-box">
      <h3>technical skills</h3>
      <div class="skills">
        <span>python</span>
        <span>c/c#</span>
        <span>java</span>
        <span>kali linux tools</span
      
    </div>
    </div>

    <div class="skill-box">
      <h3>soft skliils</h3>
      <div class="skills">
        <span>communication</span>
        <span>problem-sloving </span>
        <span>Team management </span>
        <span>Leadreship qualities</span>
      </div>
    </div>

    <div class="skill-box">
      <h3>Backend</h3>
      <div class="skills">
        <span>Node.js</span>
        <span>Express.js</span>
        <span>REST APIs</span>
        <span>Authentication</span>
      </div>
    </div>
    <div class="skill-box">
      <h3>Languages</h3>
      <div class="skills">
        <span>JAVA</span>
        <span>Python</span>
        <span>C++</span>
      </div>
    </div>
  </section>

  <!-- Tech Stack Section -->
  <section id="tech" class="section">
    <h2>Tech Stack</h2>
    <div class="stack">
      
      <span>DSA</span>
      <span>MongoDB</span>
      <span>Git & GitHub</span>
      <span>SQL</span>
      <span>API Integration</span>
      <span>Cloud Basics</span>
      <span>Prompt Engineering</span>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section light">
    <h2>Contact Me</h2>
    <p>Email: prathikshaasenthilkumar7@gmail.com</p>
    <p>Location:Chennai,India</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Prathikshaa | ethical hacker</p>
  </footer>

</body>
</html>

 {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", sans-serif;
}

body {
  background:;
  color: rgb(140, 102, 102);
  line-height: 1.6;
}

/* Navbar */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 10%;
  background: #020332;
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo {
  color: #e7e6ec;
  font-size: 1.6rem;
}

nav a {
  margin-left: 25px;
  text-decoration: none;
  color: #fff;
  font-weight: 500;
  transition: 0.3s;
}

nav a:hover {
  color: #554e79;
}

/* Hero */
.hero {
  height: 90vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero h2 {
  font-size: 3.2rem;
}

.hero span {
  background: #530745;
  
}

.hero p {
  margin-top: 10px;
  font-size: 1.2rem;
  opacity: 0.85;
}

.tagline {
  margin-top: 8px;
  font-size: 1rem;
  opacity: 0.6;
}

.hero-image img {
  border-radius: 20px;
  width: 250px;
  height: 250px;
  object-fit: cover;
}

/* Sections */
.section {
  padding: 80px 10%;
  text-align: center;
}

.section h2 {
  font-size: 2.3rem;
  margin-bottom: 25px;
  color: #cc8ec2;

}

.section p {
  max-width: 800px;
  margin: auto;
  opacity: 0.85;
}

.light {
  background: #020332;
}

/* Skills */
.skill-box {
  margin-bottom: 40px;
}

.skill-box h3 {
  margin-bottom: 15px;
  color: #fff;
  font-size: 1.3rem;
}

.skills, .stack {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}

.skills span {
  background: #020332;
  border: 1px solid #ece3e3;
  color: #fff;
  padding: 10px 18px;
  border-radius: 25px;
  font-size: 0.9rem;
  transition: 0.3s;
}

.skills span:hover {
  background: #447fd1;
  transform: translateY(-3px);
}

/* Tech Stack */
.stack span {
  background: #020332;
  border: 1px solid #f8f1f1;
  color: #fff;
  padding: 10px 18px;
  border-radius: 25px;
  font-size: 0.9rem;
  transition: 0.3s;
}

.stack span:hover {
  background: #3766a9;
  transform: translateY(-3px);
}

.mern {
  border: 1px solid #ff3c3c !important;
  color: #ff3c3c;
  font-weight: 600;
}

/* Footer */
footer {
  background: #0f0f0f;
  padding: 20px;
  text-align: center;
  font-size: 0.9rem;
  opacity: 0.6;
}
```


## OUTPUT
<img width="1875" height="1098" alt="Screenshot 2026-02-05 112119" src="https://github.com/user-attachments/assets/c34b8ae5-0eab-4641-b855-31965ed4d0a3" />

<img width="1918" height="1094" alt="Screenshot 2026-02-05 111800" src="https://github.com/user-attachments/assets/7f7282df-b733-4e53-8c15-fa31972f0e08" />

<img width="1910" height="1093" alt="Screenshot 2026-02-05 111911" src="https://github.com/user-attachments/assets/23f964c6-fa30-42af-9177-18d64af0bcab" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
