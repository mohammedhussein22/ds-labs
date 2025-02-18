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
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I'm a Data Scientist passionate about Machine Learning, AI, and Data Visualization.</p>
    </section>
    
    <section id="portfolio">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>A short description of the project.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>A short description of the project.</p>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: your.email@example.com</p>
        <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
    </section>
    
    <footer>
        <p>&copy; 2024 My Portfolio. All Rights Reserved.</p>
    </footer>
</body>
</html>

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Header Styling */
header {
    background: #333;
    color: white;
    padding: 20px;
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
    font-weight: bold;
}

/* Section Styling */
section {
    padding: 40px;
    text-align: center;
}

#about, #portfolio, #contact {
    background: white;
    margin: 20px auto;
    width: 80%;
    border-radius: 10px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
}

/* Portfolio Projects */
.project {
    background: #ddd;
    margin: 10px auto;
    padding: 15px;
    border-radius: 5px;
    width: 60%;
}

/* Contact Section */
a {
    color: #007BFF;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    text-align: center;
    background: #333;
    color: white;
    padding: 10px;
    margin-top: 20px;
}

