html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - Adomako Isaac</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <a href="#home">Adomako Isaac</a>
            </div>
            <div class="nav-menu" id="nav-menu">
                <a href="#home" class="nav-link">Home</a>
                <a href="#about" class="nav-link">About</a>
                <a href="#projects" class="nav-link">Projects</a>
                <a href="#contact" class="nav-link">Contact</a>
            </div>
            <div class="hamburger" id="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Hello, I'm <span class="highlight">John Doe</span></h1>
            <p>Full Stack Developer & UI/UX Enthusiast</p>
            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">View My Work</a>
                <a href="#contact" class="btn btn-secondary">Get In Touch</a>
            </div>
        </div>
        <div class="hero-image">
            <div class="image-placeholder">
                <i class="fas fa-user fa-8x"></i>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>I'm a passionate full-stack developer with 3 years of experience creating web applications. I love turning complex problems into simple, beautiful designs.</p>
                    <div class="skills">
                        <h3>Skills</h3>
                        <div class="skill-tags">
                            <span class="skill-tag">HTML/CSS</span>
                            <span class="skill-tag">JavaScript</span>
                            <span class="skill-tag">React</span>
                            <span class="skill-tag">Node.js</span>
                            <span class="skill-tag">Python</span>
                            <span class="skill-tag">Git</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-shopping-cart fa-3x"></i>
                    </div>
                    <h3>E-Commerce Website</h3>
                    <p>A full-stack e-commerce platform with React and Node.js</p>
                    <div class="project-tech">
                        <span>React</span>
                        <span>Node.js</span>
                        <span>MongoDB</span>
                    </div>
                    <div class="project-links">
                        <a href="#" class="project-link">Live Demo</a>
                        <a href="#" class="project-link">GitHub</a>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-tasks fa-3x"></i>
                    </div>
                    <h3>Task Manager App</h3>
                    <p>A productivity app for managing daily tasks and projects</p>
                    <div class="project-tech">
                        <span>JavaScript</span>
                        <span>Firebase</span>
                        <span>CSS3</span>
                    </div>
                    <div class="project-links">
                        <a href="#" class="project-link">Live Demo</a>
                        <a href="#" class="project-link">GitHub</a>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-chart-line fa-3x"></i>
                    </div>
                    <h3>Analytics Dashboard</h3>
                    <p>Real-time data visualization dashboard for business metrics</p>
                    <div class="project-tech">
                        <span>Vue.js</span>
                        <span>Python</span>
                        <span>D3.js</span>
                    </div>
                    <div class="project-links">
                        <a href="#" class="project-link">Live Demo</a>
                        <a href="#" class="project-link">GitHub</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <span>john.doe@email.com</span>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <span>+1 (555) 123-4567</span>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>New York, NY</span>
                    </div>
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-github"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-linkedin"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                    </div>
                </div>
                <form class="contact-form" id="contact-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" rows="5" required></textarea>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 John Doe. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
