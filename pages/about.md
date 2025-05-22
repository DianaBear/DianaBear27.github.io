<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <title>Diana Barakat | Clemson Computer Science</title> -->

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
            background: #D6B3E1; /* Lilac Purple */
            border-bottom: 5px solid #F66733; /* Orange Strip */
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
            background: rgb(168, 7, 255); 
            color: #333;
        }

        /* About Me Section */
        .about {
            padding: 40px;
            text-align: center;
        }

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
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Contact Section */
        .contact {
            padding: 40px;
            background-color: #e9e9e9;
        }

        .contact-info ul {
            list-style: none;
            padding: 0;
        }

        .contact-info li {
            margin-bottom: 10px;
        }

        /* Footer */
        .footer {
            padding: 20px;
            background-color: #D6B3E1;
            text-align: center;
            color: white;
        }
    </style>
</head>
<body>


    <!-- Hero Section -->
    <header class="hero">
        <h1>About Me! 👩🏻‍💻</h1>
        <p>Learn more about my academic journey and career goals</p>
        <a href="#projects" class="cta">View My Work</a>
    </header>

    <!-- About Me Section -->
    <section class="about">
        <h2>About Me</h2>
        <p>I'm a Computer Information Systems major with a Cybersecurity minor at Clemson University, set to graduate in May 2026. I'm particularly interested in emerging technologies like artificial intelligence, machine learning, and privacy compliance in software development. I enjoy exploring how advanced algorithms and secure systems influence the digital world. Through a mix of technical and security-focused coursework, I'm developing a well-rounded skill set to navigate the fast-paced tech industry.</p>
    </section>

    <section class="about">
        <h2>My goals as a student</h2>
        <p>My goal is to become a Cybersecurity Analyst, using my skills to protect systems and secure data in an increasingly digital world. While that’s my main focus, I’m also exploring different areas of computer science to find what excites me most. Whether it’s diving into AI, analyzing cybersecurity threats, or experimenting with software development, I see this exploration as a way to grow both personally and professionally. I’m driven by a passion for learning, adapting, and making a meaningful impact in the ever-changing tech industry.</p>
    </section>

<section class="about">
        <h2>Great Books That Changed My Perspective on Computer Science</h2>
        <h3><em>Artificial Unintelligence</em> by Meredith Broussard</h3>
        <p>TThis book challenged the idea that technology is objective. It made me think critically about how computers often fail to understand the complexities of real world problems, especially when it comes to people and social issues.</p>

        <h3><em>Weapons of Math Destruction</em> by Cathy O’Neil</h3>
        <p>This book explores how algorithms can reinforce inequality at scale. It pushed me to think more deeply about the ethical impact of data driven systems, especially in areas like education, policing, and finance.</p>

    </section>

    <!-- Contact Section -->
    <section class="contact">
        <h2>Contact Me</h2>
        <p>Feel free to connect with me via the following:</p>
        <ul>
            <li>Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></li>
            <li>GitHub: <a href="https://github.com/DianaBear">DianaBear</a></li>
        </ul>
    </section>

    <footer class="footer">
        <p> Last updated 2025 by DianaBear | Clemson University</p>
        <div class="footer-links">
            <a href="index.html">Home</a> |
            <a href="project.html">Projects</a> |  
            <a href="CareerOverview.html">Career</a> | 
            <a href="Resume.html">Resume</a> |
        </div>
    </footer>


</body>
</html>
