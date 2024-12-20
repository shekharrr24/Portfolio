# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shekhar chaudhary | Portfolio</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f9;
        }

        /* Header */
        header {
            background: #35424a;
            color: #ffffff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
        }

        /* Navigation */
        nav {
            background: #222;
            color: #fff;
            display: flex;
            justify-content: center;
            padding: 0.5rem 0;
        }

        nav a {
            color: #ffffff;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #1803cd;
        }

        /* Container */
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 1rem;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        /* Section */
        section {
            margin-bottom: 2rem;
        }

        section h2 {
            border-bottom: 2px solid #00bcd4;
            display: inline-block;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
            color: #35424a;
        }

        .intro p {
            font-size: 1.1rem;
            line-height: 1.8;
            text-align: justify;
        }

        /* Skills */
        .skills ul {
            display: flex;
            flex-wrap: wrap;
            list-style: none;
        }

        .skills li {
            background: #00bcd4;
            color: #fff;
            margin: 0.5rem;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            font-weight: bold;
        }

        /* Projects */
        .projects .project-card {
            background: #f4f4f4;
            border: 1px solid #ddd;
            margin-bottom: 1rem;
            padding: 1rem;
            border-radius: 6px;
            transition: box-shadow 0.3s;
        }

        .projects .project-card:hover {
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        /* Contact */
        .contact p {
            font-size: 1.1rem;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #222;
            color: #fff;
        }

        /* Responsive */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            nav a {
                margin: 0 0.5rem;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Shekhar chaudhary</h1>
        <p>B.Tech in Computer Science and Engineering | KIET Ghaziabad</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#languages">Languages</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Container -->
    <div class="container">
        <!-- About Section -->
        <section id="about" class="intro">
            <h2>About Me</h2>
            <p>
                Hello! My name is Shekhar chaudhary. I am pursuing B.Tech in Computer Science and Engineering from KIET Ghaziabad. I have a keen interest in web development, competitive programming, and creative media editing.
            </p>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Git</li>
                <li>Data Structure and Algorithm(C language)</li>
                <li>DaVinci Resolve</li>
            </ul>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="projects">
            <h2>Projects</h2>
            <div class="project-card">
                <h3>Browser</h3>
                <p>A website used to help individuals managing their everday waste. Built using HTML and CSS.</p>
            </div>
            <div class="project-card">
                <h3>Video Editing Project</h3>
                <p>A short film edited using DaVinci Resolve, focusing on transitions and sound design.</p>
            </div>
        </section>

        <!-- Languages Section -->
        <section id="languages" class="skills">
            <h2>Languages</h2>
            <ul>
                <li>English</li>
                <li>Hindi</li>
                <li>French</li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact</h2>
            <p>
                Email: <strong>chaudharyshekhar924@gmail.com</strong> <br>
                LinkedIn: <a href="https://www.linkedin.com/in/shekhar-chaudhary-5b839b329?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app target="_blank">linkedin.com/in/Shekharchaudhary</a>
            </p>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Shekhar chaudhary. All Rights Reserved.</p>
    </footer>
</body>
</html>
