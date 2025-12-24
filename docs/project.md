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

        <style>
        /* Projects Section */
        .projects {
            padding: 40px;
            background-color: #F2F3F2; /* matches page background */
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
            padding: 22px;
            background-color: #D6B3E1; /* Lilac */
            border-radius: 12px;
            border-top: 6px solid #F66733; /* Orange accent */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.12);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 10px 18px rgba(0, 0, 0, 0.18);
        }

        .project-card h3 {
            color: #F66733; /* Orange titles */
            margin-bottom: 10px;
        }

        .project-card p {
            color: #333;
            font-size: 1rem;
            line-height: 1.4;
        }
        </style>

    </style>
</head>
<body>

    <!-- Hero Section -->
    <header class="hero">
        <h1>My Projects 👩🏻‍💻</h1>
        <p>Explore some of the projects.</p>
    </header>

    <!-- Projects Section -->
<section class="projects" id="projects">
    <h2>My Projects</h2>
    <div class="project-container">
        <div class="project-card">
            <h3>Palmetto Blooms – Hackathon Project</h3>
            <p>Developed a mobile app that identifies bloom stages and flags early pest risks. Designed the UI/flow and integrated environmental inputs to improve classification accuracy. (Fall 2025)</p>
        </div>
        <div class="project-card">
            <h3>Skincare App – Personalized Routine Tracker</h3>
            <p>Built a quiz-based skin type assessment and recommendation engine, with mobile-friendly routine logging and progress tracking. (2025)</p>
        </div>
        <div class="project-card">
            <h3>Gender Gap in Computer Science – Independent Research</h3>
            <p>Analyzed 10+ years of IPEDS datasets (50k+ data points) to visualize long-term gender disparities in CS enrollment and explored diversity and inclusion challenges. (Spring 2025)</p>
        </div>
        <div class="project-card">
            <h3>Weather Prediction Using Machine Learning</h3>
            <p>Compiled 100 years of Greenville weather data and trained predictive models (Linear Regression, Random Forest) in Python, achieving 12–18% improvement over baseline accuracy. (Summer 2024)</p>
        </div>
                <div class="project-card">
            <h3>Checkers Game Project (Java)</h3>
            <p>Built a fully functional checkers game using Java, implementing game logic, player interaction, and rule enforcement.</p>
        </div>

        <div class="project-card">
            <h3>Data Science Project – Gender Gap in Computer Science (Python)</h3>
            <p>Used IPEDS data to analyze and visualize gender disparities in computer science enrollment nationally and at Clemson University.</p>
        </div>

        <div class="project-card">
            <h3>US vs. France Government Comparison (R)</h3>
            <p>Compared governmental structures and policies of the United States and France using data analysis and visualization in R.</p>
        </div>

        <div class="project-card">
            <h3>Personal Website (Jekyll + GitHub Pages)</h3>
            <p>Designed and deployed a personal portfolio website using Jekyll and GitHub Pages to showcase projects, experience, and skills.</p>
        </div>

        <div class="project-card">
            <h3>Microservices Project – Spotify API</h3>
            <p>Developed an API-driven application integrating the Spotify API to create personalized playlists, add predefined songs, and retrieve user data.</p>
        </div>

        <div class="project-card">
            <h3>Stack Implementation with Design Patterns</h3>
            <p>Implemented a stack data structure while applying design patterns such as Factory and Singleton to improve modularity and scalability.</p>
        </div>

        <div class="project-card">
            <h3>Typing Game (Python)</h3>
            <p>Created a typing practice game supporting custom text input (notes or lyrics) and tracking typing speed (WPM) for skill improvement.</p>
        </div>
        <div class="project-card">
            <h3>TigerChow Postman API</h3>
            <p>Created and tested API specifications for the TigerChow application using Postman, ensuring smooth backend/frontend integration and endpoint documentation.</p>
        </div>
        <div class="project-card">
            <h3>DianaBear Typing Game (Python/C)</h3>
            <p>Developed a typing game to practice notes or lyrics, supporting custom text input and tracking typing speed (WPM).</p>
        </div>
        <div class="project-card">
            <h3>SDLC & Agile Methodology Project</h3>
            <p>Served as Scrum Master for the TigerChow project, managing Trello boards, sprint planning, and team coordination while applying SDLC and Agile principles.</p>
        </div>
        <div class="project-card">
            <h3>Image Stacking in C</h3>
            <p>Implemented noise reduction in PPM images using dynamic memory allocation and image stacking techniques in C.</p>
        </div>
    </div>
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