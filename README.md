<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Portfolio - Syeda Rimsha Chishti</title>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="styles.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
      <style>
        /* General Styling */
* {
    box-sizing: border-box; /* Include padding and border in width calculations */
    margin: 0; /* Reset margin for all elements */
    padding: 0; /* Reset padding for all elements */
}

body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #0d1117;
    color: #c9d1d9;
    overflow-x: hidden; /* Hide horizontal scroll */
}

/* Header Section */
header {
    height: 20vh;
    width: 100vw; /* Ensure full width */
    text-align: center;
    padding: 2rem;
    background-image: url(https://img.freepik.com/free-vector/abstract-blue-circle-black-background-technology_1142-12714.jpg?w=1480&t=st=1728040414~exp=1728041014~hmac=146e3a93f5f8baa01a67d819a4baa95168e9e7bc67fe86cccc5f1079d5349af2);
    margin-bottom: 2rem;
    background-size: cover; /* Make sure the background covers the whole area */
    background-position: center; /* Center the background image */
}

h1 {
    font-size: 2.5rem;
    margin: 0.5rem 0;
    color: #fff;
}

p {
    font-size: 1.2rem;
    color: #8b949e;
}

.introduction {
    text-align: center;
    margin-bottom: 2rem;
    padding: 0 1.5rem;
}

.introduction h2 {
    font-size: 2rem;
    color: #58a6ff;
}

.introduction p {
    font-size: 1.1rem;
    color: #8b949e;
    max-width: 800px;
    margin: 0 auto;
}

.wave-icon {
    font-size: 1.5rem;
}

/* Horizontal Line Styling */
.divider {
    border: 0;
    height: 1px;
    background-image: linear-gradient(to right, rgba(255, 255, 255, 0), rgba(88, 166, 255, 0.75), rgba(255, 255, 255, 0));
    margin: 2rem 0;
}

/* Skills Section */
.skills-section {
    padding: 2rem 1.5rem;
}

.skills-section h2 {
    text-align: center;
    font-size: 2rem;
    margin-bottom: 2rem;
    color: #58a6ff;
}

.skills {
    display: flex;
    justify-content: center;
    margin-bottom: 2rem;
    flex-wrap: wrap; /* Allow wrapping of skills */
}

.skill-category {
    margin: 1rem;
    text-align: center;
}

.skill-category h3 {
    font-size: 1.5rem;
    color: #58a6ff;
    margin-bottom: 1rem;
}

.skill-badge {
    display: inline-block;
    padding: 0.5rem 1rem;
    background-color: #444;
    color: #fff;
    border-radius: 5px;
    margin: 0.5rem;
    font-size: 1rem;
    transition: background-color 0.3s ease;
}

.skill-badge i {
    margin-right: 0.5rem;
}

.skill-badge:hover {
    background-color: #58a6ff;
    color: #0d1117;
}

/* Footer Styling */
footer {
    background-color: #161b22;
    padding: 1.5rem 0;
    text-align: center;
    color: #c9d1d9;
}

.footer-content {
    max-width: 1000px;
    margin: 0 auto;
    padding: 0 1.5rem;
}

footer p {
    margin: 0;
    font-size: 1rem;
    color: #8b949e;
}

.social-icons {
    margin-top: 1rem;
}

.social-icons a {
    color: #8b949e;
    font-size: 1.5rem;
    margin: 0 0.5rem;
    text-decoration: none;
    transition: color 0.3s ease;
}

.social-icons a:hover {
    color: #58a6ff;
}

/* Responsive Adjustments */
@media (max-width: 768px) {
    header {
        padding: 1.5rem; /* Adjust padding on smaller screens */
    }

    .introduction p {
        font-size: 1rem; /* Smaller text on smaller screens */
    }

    .skills {
        flex-direction: column; /* Stack skills vertically on smaller screens */
        align-items: center; /* Center align on smaller screens */
    }

    .skill-badge {
        font-size: 0.9rem; /* Smaller font size for badges */
    }
}

        </style>
    </head>
    
    
<body>

    <!-- Header Section -->
    <header>
        <div class="profile-header">
            <h1>Syeda Rimsha Chishti</h1>
            <p>Web Developer & UI/UX Enthusiast</p>
        </div>
    </header>

    <!-- Introduction -->
    <section class="introduction">
        <h2>Hello People <span class="wave-icon">👋</span></h2>
        <p style="font-family: 'Quicksand',sans-serif;">
            <br>
            I am a <strong>PHP Developer with a flair for creativity!</strong> My expertise lies in crafting robust and efficient web applications that captivate users at every turn. With a strong command of PHP and the Laravel framework, I excel at building smooth, dynamic websites that provide outstanding user experiences. Driven by a passion for innovative design and cutting-edge technology, I strive to create visually appealing interfaces that elevate the art of web development in every project I undertake.
        </p>
    </section>
    
    
    <hr class="divider"> <!-- Horizontal Line -->

    <!-- Skills Section -->
    <section class="skills-section">
        <h2>Skills</h2>
        
        <!-- Web Development Skills -->
        <div class="skills">
            <div class="skill-category">
                <h3>Web Development</h3>
                <span class="skill-badge" style="background-color: #005eff;"><i class="fab fa-php"></i> PHP</span>
                <span class="skill-badge" style="background-color: #ff4b00;"><i class="fas fa-code"></i> Laravel</span>
                <span class="skill-badge" style="background-color: #ff5700;"><i class="fab fa-html5"></i> HTML5</span>
                <span class="skill-badge" style="background-color: #264de4;"><i class="fab fa-css3-alt"></i> CSS3</span>
                <span class="skill-badge" style="background-color: #f7df1e; color: black;"><i class="fab fa-js"></i> ECMAScript</span>
                <span class="skill-badge" style="background-color: #563d7c;"><i class="fab fa-bootstrap"></i> Bootstrap</span>
            </div>
        </div>

        <hr class="divider"> <!-- Horizontal Line -->

        <!-- UI/UX Skills -->
        <div class="skills">
            <div class="skill-category">
                <h3>UI/UX Design</h3>
                <span class="skill-badge" style="background-color: #f24e1e;"><i class="fas fa-drafting-compass"></i> Figma</span>
                <span class="skill-badge" style="background-color: #ff61f6;"><i class="fas fa-pencil-alt"></i> Adobe XD</span>
                <span class="skill-badge" style="background-color: #0085ff;"><i class="fas fa-pencil-ruler"></i> UI/UX Design</span>
            </div>
        </div>

        <hr class="divider"> <!-- Horizontal Line -->

        <!-- SEO Skills -->
        <div class="skills">
            <div class="skill-category">
                <h3>SEO</h3>
                <span class="skill-badge" style="background-color: #00b140;"><i class="fas fa-search"></i> Search Engine Optimization (SEO)</span>
            </div>
        </div>

        <hr class="divider"> <!-- Horizontal Line -->

        <!-- IDEs Section -->
        <div class="skills">
            <div class="skill-category">
                <h3>IDEs</h3>
                <span class="skill-badge" style="background-color: #0078d7;"><i class="fas fa-code"></i> Visual Studio Code</span>
                <span class="skill-badge" style="background-color: #3ddc84;"><i class="fas fa-mobile-alt"></i> Android Studio</span>
            </div>
        </div>

        <hr class="divider"> <!-- Horizontal Line -->

        <!-- OS Section -->
        <div class="skills">
            <div class="skill-category">
                <h3>Operating Systems</h3>
                <span class="skill-badge" style="background-color: #ff7f50;"><i class="fab fa-linux"></i> Linux</span>
                <span class="skill-badge" style="background-color: #dd4814;"><i class="fab fa-ubuntu"></i> Ubuntu</span>
                <span class="skill-badge" style="background-color: #0078d7;"><i class="fab fa-windows"></i> Windows</span>
                <span class="skill-badge" style="background-color: #3ddc84;"><i class="fab fa-android"></i> Android</span>
            </div>
        </div>
    </section>


   <!-- Footer Section -->
<footer>
    <div class="footer-content">
        <p>© 2024 Syeda Rimsha Chishti. All rights reserved.</p>
        <div class="social-icons">
            <a href="https://www.linkedin.com/in/syeda-rimsha-558a90328/" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://www.facebook.com/profile.php?id=100095138036201" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="mailto:syedarimshachishti3@gmail.com"><i class="fas fa-envelope"></i></a>
        </div>
    </div>
</footer>

</body>
</html>

