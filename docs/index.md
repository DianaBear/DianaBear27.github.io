<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diana Barakat | Clemson Computer Science</title>

    <style>
        /* Global Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F2F3F2;
            color: #333;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px 30px;
            background: #D6B3E1;
            border-bottom: 5px solid #F66733;
            color: white;
            font-size: 1.5rem;
            font-weight: bold;
        }

        /* Hero Section */
        .hero {
            background: #D6B3E1;
            color: white;
            padding: 80px 20px;
            border-bottom: 5px solid #F66733;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
        }

        .hero p {
            font-size: 1.3rem;
        }

        .cta {
            display: inline-block;
            padding: 12px 24px;
            background: white;
            color: #F66733;
            font-weight: bold;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 20px;
            transition: 0.3s;
        }

        .cta:hover {
            background: #A807FF;
            color: #fff;
        }

        /* About Section */
        .about {
            padding: 40px;
            text-align: center;
        }

        /* Skills Section */
        .skills {
            padding: 40px;
            background-color: #f9f9f9;
            text-align: center;
        }

        .skills ul {
            list-style: none;
            padding: 0;
        }

        .skills li {
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        /* Projects Section */
        .projects {
            padding: 40px;
            background-color: #F2F3F2;
            text-align: center;
        }

        .project-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .project-card {
            padding: 22px;
            background-color: #D6B3E1;
            border-radius: 12px;
            border-top: 6px solid #F66733;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.12);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 10px 18px rgba(0, 0, 0, 0.18);
        }

        .project-card h3 {
            color: #F66733;
            margin-bottom: 10px;
        }

        /* Contact Section */
        .contact {
            padding: 40px;
            background-color: #e9e9e9;
            text-align: center;
        }

        .contact-info ul {
            list-style: none;
            padding: 0;
        }

        .contact-info li {
            margin-bottom: 10px;
        }

        .contact-info a {
            color: #F66733;
            text-decoration: none;
            font-weight: bold;
        }

        .contact-info a:hover {
            color: #D45F25;
            text-decoration: underline;
        }

        /* Footer */
        .footer {
            padding: 20px;
            background-color: #D6B3E1;
            text-align: center;
            color: white;
        }

        .footer-links a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            margin: 0 10px;
        }

        .footer-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Welcome to My Page! 👩🏻‍💻</h1>
        <p>Computer Science Student @ Clemson University | Incoming Intern @ Vertiv</p>
        <a href="#projects" class="cta">View My Work</a>
    </header>

    <!-- About -->
    <section class="about">
        <h2>About Me</h2>
        <p>I am a Computer Information Systems major with a Cybersecurity minor at Clemson University. I have hands-on experience in IT operations and technical support through my internship at Vertiv.</p>
        <p>As an undergraduate researcher, I focused on privacy compliance in software development and explored quantum computing topics.</p>
        <p>I enjoy learning new programming languages, working with APIs, and exploring emerging technologies.</p>
    </section>

    <!-- Skills -->
    <section class="skills">
        <h2>Skills & Expertise</h2>
        <ul>
            <li>Languages: C, C++, Python, Java, R</li>
            <li>Web: HTML, JavaScript</li>
            <li>APIs: REST, Postman</li>
            <li>Tools: Git, GitHub</li>
        </ul>
    </section>

    <!-- Projects -->
    <section class="projects" id="projects">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <h3>TigerChow API</h3>
                <p>Developing an API to streamline campus food orders using Postman and microservices.</p>
            </div>
            <div class="project-card">
                <h3>Image Stacking in C</h3>
                <p>Noise reduction in PPM images using dynamic memory allocation in C.</p>
            </div>
            <div class="project-card">
                <h3>Weather Predictor (Python)</h3>
                <p>Analyzed weather patterns and predicted future conditions using machine learning.</p>
            </div>
            <div class="project-card">
                <h3>DianaBear Typing Game</h3>
                <p>A typing game that tracks WPM and helps practice notes or lyrics.</p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section class="contact">
        <h2>Contact Me</h2>
        <ul class="contact-info">
            <li>Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></li>
            <li>GitHub: <a href="https://github.com/DianaBear">DianaBear</a></li>
        </ul>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>Last updated 2025 by DianaBear | Clemson University</p>
        <div class="footer-links">
            <a href="project.html">Projects</a> |
            <a href="about.html">About</a> |
            <a href="CareerOverview.html">Career</a> |
            <a href="Resume.html">Resume</a>
        </div>
    </footer>

</body>
</html>
