<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Projects</title>

    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F2F3F2;
            color: #333;
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
            cursor: pointer;
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

        /* Image preview (hidden by default) */
        .project-preview {
            max-height: 0;
            overflow: hidden;
            margin-top: 12px;
            transition: max-height 0.4s ease;
        }

        .project-preview img {
            width: 100%;
            border-radius: 8px;
            margin-top: 10px;
        }

        .project-card.active .project-preview {
            max-height: 300px;
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
            margin: 0 8px;
        }

        .footer-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

<!-- Hero -->
<header class="hero">
    <h1>My Projects 👩🏻‍💻</h1>
    <p>Click a project to preview it</p>
</header>

<!-- Projects -->
<section class="projects" id="projects">
    <div class="project-container">

        <div class="project-card" onclick="toggleProject(this)">
            <h3>Palmetto Blooms – Hackathon Project</h3>
            <p>Mobile app that identifies bloom stages and flags early pest risks.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="Palmetto Blooms preview">
            </div>
        </div>

        <div class="project-card" onclick="toggleProject(this)">
            <h3>Skincare App – Personalized Routine Tracker</h3>
            <p>Quiz-based skin type assessment with routine tracking.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="Skincare app preview">
            </div>
        </div>

        <div class="project-card" onclick="toggleProject(this)">
            <h3>Gender Gap in Computer Science</h3>
            <p>Analyzed 10+ years of IPEDS data to visualize enrollment trends.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="Gender gap data preview">
            </div>
        </div>

        <div class="project-card" onclick="toggleProject(this)">
            <h3>Weather Prediction (Python)</h3>
            <p>Machine learning models trained on 100 years of weather data.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="Weather ML preview">
            </div>
        </div>

        <div class="project-card" onclick="toggleProject(this)">
            <h3>Checkers Game (Java)</h3>
            <p>Turn-based checkers game with full rule enforcement.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="Checkers game preview">
            </div>
        </div>

        <div class="project-card" onclick="toggleProject(this)">
            <h3>Personal Website</h3>
            <p>Portfolio site built with Jekyll and GitHub Pages.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="Website preview">
            </div>
        </div>

        <div class="project-card" onclick="toggleProject(this)">
            <h3>TigerChow Postman API</h3>
            <p>Designed and tested REST APIs for food ordering system.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="TigerChow API preview">
            </div>
        </div>

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

<!-- JS -->
<script>
function toggleProject(card) {
    card.classList.toggle("active");
}
</script>

</body>
</html>
