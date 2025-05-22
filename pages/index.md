
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
            background: #D6B3E1; /* Lilac Purple */
            border-bottom: 5px solid #F66733; /* Orange Strip */
            color: white;
            font-size: 1.5rem;
            font-weight: bold;
        }

        /* Hero Section */
        .hero {
            background: #D6B3E1; /* Lilac Purple */
            color: white;
            padding: 80px 20px;
            border-bottom: 5px solid #F66733; /* Orange Strip */
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

        /* About Me Section */
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
            list-style-type: none;
            padding: 0;
        }

        .skills li {
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        /* Projects Section */
        .projects {
            padding: 40px;
            background-color: #f7f7f7;
            text-align: center;
        }

        .project-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            justify-content: center;
            margin-top: 20px;
        }

        .project-card {
            padding: 20px;
            background: #D6B3E1; /* Light Orange */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }

        .project-card h3 {
            color: #F66733;
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
            color: #F66733; /* Orange link color */
            text-decoration: none;
            font-weight: bold;
        }

    .contact-info a:hover {
        color: #D45F25; /* Darker orange on hover */
        text-decoration: underline;
    }

        /* Footer */
        .footer {
            padding: 20px;
            background-color: #D6B3E1;
            text-align: center;
            color: white;
        }

        .footer-links {
            margin-top: 10px;
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

    <!-- About Me Section -->
    <section class="about">
        <h2>About Me</h2>
        <p>I'm a Computer Information Systems major with a Cybersecurity minor at Clemson University. Currently, I am an IT Site Intern at Vertiv, where I support onsite infrastructure and gain hands on experience in IT operations. This includes exposure to enterprise systems, cloud computing, and day to day technical support at a global technology company.
        
        I've also worked as an undergraduate researcher focused on privacy compliance in software development and explored topics in quantum computing. Starting Fall 2025, I'll be part of a creative inqury team researching humanoid robotics for everyday automation.</p>

        <p>I enjoy learning new programming languages, working with APIs, and  diving into research on emerging technologies. Whether it’s cybersecurity, software development, or data analysis, I’m always excited to take on new challenges in tech!</p>

    </section>

    <!-- Skills Section -->
    <section class="skills">
        <h2>Skills & Expertise</h2>
        <p>Here are some of the skills I’ve developed throughout my studies and projects:</p>
        <ul>
            <li>Programming Languages: C, C++, Python, Java, and R</li>
            <li>Web Development: HTML & JavaScript</li>
            <li>APIs: RESTful APIs, Postman</li>
            <li>Version Control: Git, GitHub</li>
            <li>Business & Accounting knowledge from additional coursework</li>
        </ul>
    </section>

<!-- Projects Section -->
<section class="projects" id="projects">
    <h2>My Projects</h2>
    <div class="project-container">
        <div class="project-card">
            <h3>TigerChow API</h3>
            <p>Developing an API to streamline campus food orders using Postman & microservices.</p>
        </div>
        <div class="project-card">
            <h3>Image Stacking in C</h3>
            <p>Noise reduction in PPM images using dynamic memory allocation in C.</p>
        </div>
        <div class="project-card">
            <h3>Weather Predictor (Python)</h3>
            <p>Analyzed weather patterns and predicted future conditions using machine learning algorithms.</p>
        </div>
        <div class="project-card">
            <h3>DianaBear Typing Game (C)</h3>
            <p>A fun typing game that tracks your typing speed (WPM) and helps practice notes or lyrics.</p>
        </div>
    </div>
</section>

<style>
    /* Projects Section */
    .projects {
        padding: 40px;
        background-color: #f7f7f7;
    }

    .project-container {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 20px;
    }

    .project-card {
        padding: 20px;
        background: #D6B3E1; /* Light Orange Hue */
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
</style>


    <!-- Contact Section -->
    <section class="contact">
        <h2>Contact Me</h2>
        <div class="contact-info">
            <p>Feel free to connect with me via the following:</p>
            <ul>
                <li>Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></li>
                <li>GitHub: <a href="https://github.com/DianaBear">DianaBear</a></li>
            </ul>
        </div>
    </section>

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