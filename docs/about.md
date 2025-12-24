
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Diana Barakat</title>
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
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            background: #D6B3E1;
            border-bottom: 5px solid #F66733;
            color: white;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
            padding: 0;
        }

        .nav-links li {
            display: inline;
        }

        .nav-links li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 10px;
        }

        .nav-links li a:hover {
            text-decoration: underline;
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
            background: rgb(168, 7, 255); 
            color: #333;
        }

        /* Section Styling */
        .about {
            padding: 40px;
            text-align: center;
            max-width: 900px;
            margin: auto;
        }

        .about h2 {
            color: #6a4c9c;
            margin-bottom: 15px;
        }

        .about h3 {
            margin-top: 20px;
            margin-bottom: 5px;
            color: #444;
        }

        .about p {
            line-height: 1.6;
            margin-bottom: 15px;
        }

        /* Contact Section */
        .contact {
            padding: 40px;
            background-color: #e9e9e9;
            max-width: 900px;
            margin: auto;
        }

        .contact ul {
            list-style: none;
            padding: 0;
        }

        .contact li {
            margin-bottom: 10px;
        }

        .contact a {
            color: #F66733;
            text-decoration: none;
        }

        .contact a:hover {
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
        <h1>About Me 👩🏻‍💻</h1>
        <p>Learn more about my academic journey and career goals</p>
        <a href="#projects" class="cta">View My Work</a>
    </header>

    <!-- About Me Section -->
    <section class="about">
        <h2>About Me</h2>
        <p>I am a Computer Information Systems major with a Cybersecurity minor at Clemson University, graduating in May 2026. I have a strong interest in emerging technologies, including artificial intelligence, machine learning, and software privacy compliance. I enjoy analyzing complex systems and exploring how secure, innovative solutions can improve digital experiences. My coursework and hands-on projects have given me a well-rounded technical and security-focused skill set, preparing me for the fast-paced tech industry.</p>
    </section>

    <section class="about">
        <h2>My Goals as a Student</h2>
        <p>My primary goal is to become a Cybersecurity Analyst, protecting systems and safeguarding data in a technology-driven world. I am intentionally exploring different areas of computer science to identify what challenges and excites me most. From AI to cybersecurity threats and software development, I am focused on growing professionally while developing critical thinking and problem-solving skills. I am driven to learn, adapt, and make meaningful contributions in an ever-evolving field.</p>
    </section>

    <section class="about">
        <h2>Books That Shaped My Perspective</h2>
        <h3><em>Artificial Unintelligence</em> by Meredith Broussard</h3>
        <p>This book challenges the notion that technology is inherently objective, highlighting how systems can fail to account for human and societal complexities.</p>

        <h3><em>Weapons of Math Destruction</em> by Cathy O’Neil</h3>
        <p>This work explores how algorithms can perpetuate inequality at scale, pushing readers to consider the ethical implications of data-driven decision-making in areas such as education, finance, and law enforcement.</p>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <h2>Contact Me</h2>
        <p>Connect with me through the following channels:</p>
        <ul>
            <li>Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></li>
            <li>GitHub: <a href="https://github.com/DianaBear">DianaBear</a></li>
        </ul>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>Last updated 2025 by DianaBarakat | Clemson University</p>
        <div class="footer-links">
            <a href="index.html">Home</a> |
            <a href="project.html">Projects</a> |  
            <a href="CareerOverview.html">Career</a> | 
            <a href="Resume.html">Resume</a>
        </div>
    </footer>

</body>
</html>
