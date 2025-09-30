<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Personal Website</title>
    <style>
        /* Basic styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            max-width: 900px;
            margin: auto;
            background: #fff;
            margin-top: 20px;
            border-radius: 5px;
        }
        h1, h2 {
            color: #333;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
        .profile-pic {
            display: block;
            margin: 0 auto;
            border-radius: 50%;
            width: 150px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>John Doe</h1>
        <p>Computer Science Student | Future Developer</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
        <p>
            Hi! My name is John Doe. I am currently a Computer Science student passionate 
            about coding, cybersecurity, and web development. I enjoy learning new 
            technologies and applying them to real-world projects.
        </p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><strong>Personal Portfolio:</strong> A website showcasing my skills and projects.</li>
            <li><strong>Weather App:</strong> A simple app that fetches weather data from an API.</li>
            <li><strong>Python Script Collection:</strong> Small utilities for automation.</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:johndoe@email.com">johndoe@email.com</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/johndoe" target="_blank">linkedin.com/in/johndoe</a></p>
        <p>GitHub: <a href="https://github.com/johndoe" target="_blank">github.com/johndoe</a></p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 John Doe. All rights reserved.</p>
    </footer>

</body>
</html>
