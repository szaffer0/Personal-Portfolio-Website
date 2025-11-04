# Personal-Portfolio-Website
✅ Features:  Fully responsive basic portfolio  Modern color scheme (blue + white)  Easy to customize for your name and projects
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Syed Zaffer</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I’m a passionate web developer with experience in HTML, CSS, and Python. 
        I enjoy building creative and responsive websites.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills-list">
            <span>HTML</span>
            <span>CSS</span>
            <span>Python</span>
            <span>Django</span>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>To-Do List App</h3>
            <p>A simple Python-based web app to manage daily tasks efficiently.</p>
        </div>
        <div class="project-card">
            <h3>Student Management System</h3>
            <p>A Django web application for managing student data and performance.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:zaffer@example.com">zaffer@example.com</a></p>
        <p>LinkedIn: <a href="#" target="_blank">linkedin.com/in/zaffer</a></p>
    </section>

    <footer>
        <p>© 2025 Syed Zaffer | All Rights Reserved</p>
    </footer>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: "Poppins", sans-serif;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background: #0d6efd;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    margin-top: 10px;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: 500;
}

section {
    padding: 50px;
    text-align: center;
}

.skills-list span {
    display: inline-block;
    background: #0d6efd;
    color: white;
    margin: 10px;
    padding: 10px 15px;
    border-radius: 20px;
}

.project-card {
    background: white;
    margin: 20px auto;
    padding: 20px;
    width: 70%;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    border-radius: 10px;
}

footer {
    background: #0d6efd;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}

</body>
</html>
