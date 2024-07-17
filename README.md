# Alfido-Tech-webdevelopment2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#achievements">Achievements</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Brief introduction about yourself.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>Project Title</h3>
            <p>Description of the project.</p>
        </div>
        <!-- Add more project cards here -->
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Skill 1</li>
            <li>Skill 2</li>
            <li>Skill 3</li>
        </ul>
    </section>

    <section id="achievements">
        <h2>Achievements</h2>
        <ul>
            <li>Achievement 1</li>
            <li>Achievement 2</li>
            <li>Achievement 3</li>
        </ul>
    </section>

    <footer id="contact">
        <h2>Contact Me</h2>
        <p>Email: your.email@example.com</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #4CAF50;
    color: white;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 2em;
    margin: 1em;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.project-card {
    background: #f4f4f4;
    margin: 1em 0;
    padding: 1em;
    border-radius: 5px;
}

footer {
    background: #4CAF50;
    color: white;
    text-align: center;
    padding: 1em;
}
document.addEventListener('DOMContentLoaded', () => {
    console.log("Portfolio loaded successfully!");
    // Add interactivity here if needed
});
