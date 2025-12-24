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

/* Modal */
.modal {
    display: none; 
    position: fixed; 
    z-index: 100; 
    left: 0;
    top: 0;
    width: 100%; 
    height: 100%; 
    overflow: auto; 
    background-color: rgba(0,0,0,0.7);
}

.modal-content {
    background-color: #f7f7f7;
    margin: 5% auto;
    padding: 20px;
    border-radius: 12px;
    width: 80%;
    max-width: 800px;
    position: relative;
}

.modal .close {
    color: #F66733;
    position: absolute;
    top: 10px;
    right: 20px;
    font-size: 28px;
    font-weight: bold;
    cursor: pointer;
}

.modal .close:hover {
    color: #A807FF;
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

        <!-- Image Preview Card -->
        <div class="project-card" onclick="toggleProject(this)">
            <h3>Palmetto Blooms – Hackathon Project</h3>
            <p>Mobile app that identifies bloom stages and flags early pest risks.</p>
            <div class="project-preview">
                <img src="images/Image.jpeg" alt="Palmetto Blooms preview">
            </div>
        </div>

        <!-- Video Preview Card -->
        <div class="project-card" onclick="openModal('skincareModal')">
            <h3>Skincare App – Personalized Routine Tracker</h3>
            <p>Quiz-based skin type assessment with routine tracking.</p>
        </div>

        <!-- Video Modal -->
        <div id="skincareModal" class="modal">
            <div class="modal-content">
                <span class="close" onclick="closeModal('skincareModal')">&times;</span>
                <iframe 
                    src="https://drive.google.com/file/d/1FFjCQ3m7rX0kWM5FWfWl19ulW7juxcR3/preview"
                    width="100%" 
                    height="400"
                    allowfullscreen>
                </iframe>
            </div>
        </div>

        <!-- More Image Preview Cards -->
        <div class="project-card" onclick="toggleProject(this)">
            <h3>Gender Gap in Computer Science</h3>
            <p>Analyzed 10+ years of IPEDS data to visualize enrollment trends.</p>
            <div class="project-preview">
                <img src="images/womanCPSC.png" alt="Woman In Computer Science preview">
            </div>
        </div>

        <div class="project-card" onclick="toggleProject(this)">
            <h3>Weather Prediction (Python)</h3>
            <p>Machine learning models trained on 100 years of weather data.</p>
            <div class="project-preview">
                <img src="images/placeholder.png" alt="Weather ML preview">
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

function openModal(modalId) {
    document.getElementById(modalId).style.display = "block";
}

function closeModal(modalId) {
    document.getElementById(modalId).style.display = "none";
}

// Close modal if clicking outside content
window.onclick = function(event) {
    const modal = document.getElementById('skincareModal');
    if (event.target === modal) {
        modal.style.display = "none";
    }
}
</script>

</body>
</html>
