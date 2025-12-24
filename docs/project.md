<!-- <!DOCTYPE html>
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
</html> -->


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Projects | Diana Barakat</title>

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
        font-weight: bold;
        font-size: 1.2rem;
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
        margin-bottom: 10px;
    }

    .hero p {
        font-size: 1.3rem;
    }

    /* Projects Section */
    .projects {
        padding: 40px 20px;
        max-width: 1000px;
        margin: auto;
    }

    .projects h2 {
        color: #6a4c9c;
        margin-top: 40px;
        margin-bottom: 10px;
        text-align: center;
    }

    .projects p {
        text-align: center;
        max-width: 800px;
        margin: 0 auto 20px;
        line-height: 1.6;
    }

    .project-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
        margin-top: 30px;
    }

    .project-card {
        background: white;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .project-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    }

    .project-card h3 {
        color: #F66733;
        margin-bottom: 10px;
        text-align: center;
    }

    .project-card p {
        font-size: 1rem;
        text-align: center;
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

    <!-- Navbar -->
    <nav class="navbar">
        👩🏻‍💻 Diana Barakat
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>My Projects 👩🏻‍💻</h1>
        <p>Explore some of the projects I've worked on during my studies and personal development.</p>
    </header>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <div class="project-card">
            <h3>Checkers Game</h3>
            <p>A classic checkers game implemented using Java. Features AI opponent and user-friendly interface.</p>
        </div>
        <div class="project-card">
            <h3>Data Science Project (Python)</h3>
            <p>Analyzed IPEDS data to compare the number of men and women in computer science nationally and at Clemson University.</p>
        </div>
        <div class="project-card">
            <h3>US vs. France Government Comparison (R)</h3>
            <p>Comparative analysis of the US and French government systems using R and visualization tools.</p>
        </div>
        <div class="project-card">
            <h3>Personal Website (Jekyll + GitHub Pages)</h3>
            <p>Built and deployed my personal portfolio website using Jekyll, showcasing projects, skills, and resume.</p>
        </div>
        <div class="project-card">
            <h3>Spotify API Microservices Project</h3>
            <p>Integrated with Spotify API to retrieve and display information, create personalized playlists, and retrieve user data.</p>
        </div>
        <div class="project-card">
            <h3>TigerChow Postman API</h3>
            <p>Created and tested API specifications for the TigerChow application, ensuring smooth backend-frontend integration.</p>
        </div>
        <div class="project-card">
            <h3>Typing Game (Python)</h3>
            <p>A typing practice game where users can paste custom text like notes or lyrics to improve typing speed and accuracy.</p>
        </div>
        <div class="project-card">
            <h3>Stack Implementation with Design Patterns</h3>
            <p>Implemented a stack data structure using multiple design patterns, including Factory and Singleton.</p>
        </div>
        <div class="project-card">
            <h3>SDLC & Agile Methodology Project</h3>
            <p>Acted as Scrum Master for TigerChow project; managed Trello, set sprint dates, and followed Agile and SDLC best practices.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>Last updated 2025 by DianaBear | Clemson University</p>
        <div class="footer-links">
            <a href="index.html">Home</a> | 
            <a href="about.html">About</a> |  
            <a href="CareerOverview.html">Career</a> | 
            <a href="Resume.html">Resume</a>
        </div>
    </footer>

</body>
</html>
