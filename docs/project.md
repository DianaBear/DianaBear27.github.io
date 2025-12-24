<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Projects</title>
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

        /* Styling for images (code snippets) */
        img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ccc;
            border-radius: 8px;
            margin: 20px 0;
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <header class="hero">
        <h1>My Projects 👩🏻‍💻</h1>
        <p>Explore some of the projects I've worked on during my studies.</p>
    </header>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <h2>Checkers Game Project</h2>
        <p>This project is a checkers game built using [language/framework].</p>

        <h2>Data Science Project (Python)</h2>
        <p>This project uses IPEDS data to analyze the number of men and women in computer science nationally and at Clemson University.</p>

        <h2>US vs. France Government Comparison (R)</h2>
        <p>This project compares the US and French governments using R.</p>

        <!-- Add more project sections as needed -->

        <h2>Personal Website (Jekyll + GitHub Pages)</h2>
        <p>This is my personal website built using Jekyll and hosted on GitHub Pages. This website is the final version of my project!</p>

        <h2>Microservices Project: Spotify API (API Development)</h2>
        <p>This project involves integrating with the Spotify API to retrieve and display information. This API creates a personalized playlist, adds prespecified songs to playlist, and retrieves user data.</p>


        <h2>TigerChow Postman API</h2>
        <p>This project involves creating and testing the API specifications for the TigerChow application using Postman. The goal is to define, test, and document the API endpoints to ensure seamless integration between the backend and frontend of the application.</p>


        <h2>Typing Game (Python)</h2>
        <p>This project started as a tool to help me study and review notes through typing practice. The game allows you to paste in custom text, like lecture notes or study material, and it helps you type them accurately and quickly. Over time, the game was enhanced to support typing practice with song lyrics, turning it into a fun and engaging way to practice typing skills while listening to your favorite music.</p>


        <h2>Stack Implementation with Design Patterns</h2>
        <p>This project involved implementing a stack data structure with different design patterns (Factory, Singleton, etc.).</p>

        <h2>SDLC and Agile Methodology Project</h2>
        <p>During the tigerChow project, we focused on the Software Development Life Cycle (SDLC) and Agile methodologies. My group voted for me to be the Scrum Master, so I was in charge of keeping Trello updated and setting up dates.</p>
    </section>

<footer class="footer">
        <p> Last updated 2025 by DianaBear | Clemson University</p>
        <div class="footer-links">
            <a href="index.html">Home</a> |
            <a href="about.html">About</a> |  
            <a href="CareerOverview.html">Career</a> | 
            <a href="Resume.html">Resume</a> |
        </div>
    </footer>

</body>
</html>