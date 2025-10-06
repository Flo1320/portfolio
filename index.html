<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Développeur Fullstack</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg-primary: #0a0a0a;
            --bg-secondary: #1a1a1a;
            --text-primary: #ffffff;
            --text-secondary: #a0a0a0;
            --accent: #00ff88;
            --accent-glow: rgba(0, 255, 136, 0.3);
            --card-bg: rgba(255, 255, 255, 0.05);
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        [data-theme="light"] {
            --bg-primary: #ffffff;
            --bg-secondary: #f5f5f5;
            --text-primary: #0a0a0a;
            --text-secondary: #666666;
            --accent: #00cc6a;
            --accent-glow: rgba(0, 204, 106, 0.2);
            --card-bg: rgba(0, 0, 0, 0.03);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: var(--bg-primary);
            color: var(--text-primary);
            overflow-x: hidden;
            transition: var(--transition);
        }

        /* Animations */
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes slideInRight {
            from {
                opacity: 0;
                transform: translateX(50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes glow {
            0%, 100% { box-shadow: 0 0 20px var(--accent-glow); }
            50% { box-shadow: 0 0 40px var(--accent-glow), 0 0 60px var(--accent-glow); }
        }

        /* Background animated particles */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
        }

        .particle {
            position: absolute;
            width: 4px;
            height: 4px;
            background: var(--accent);
            border-radius: 50%;
            animation: float 6s ease-in-out infinite;
            opacity: 0.3;
        }

        /* Header */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 1.5rem 5%;
            background: rgba(10, 10, 10, 0.8);
            backdrop-filter: blur(10px);
            z-index: 1000;
            transition: var(--transition);
        }

        [data-theme="light"] header {
            background: rgba(255, 255, 255, 0.8);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1400px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--accent);
            text-decoration: none;
            animation: slideInLeft 0.8s ease;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
            animation: slideInRight 0.8s ease;
        }

        .nav-links a {
            color: var(--text-primary);
            text-decoration: none;
            font-weight: 500;
            position: relative;
            transition: var(--transition);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent);
            transition: width 0.3s ease;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .theme-toggle {
            background: var(--card-bg);
            border: 2px solid var(--accent);
            color: var(--text-primary);
            padding: 0.5rem 1rem;
            border-radius: 25px;
            cursor: pointer;
            transition: var(--transition);
            font-weight: 600;
        }

        .theme-toggle:hover {
            background: var(--accent);
            color: var(--bg-primary);
            transform: scale(1.05);
        }

        /* Hero Section */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            padding: 2rem 5%;
            margin-top: 80px;
        }

        .hero-content {
            max-width: 1400px;
            width: 100%;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
            z-index: 1;
        }

        .hero-text h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
            background: linear-gradient(135deg, var(--accent), #00aaff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: fadeIn 1s ease;
        }

        .hero-text h2 {
            font-size: 2rem;
            color: var(--text-secondary);
            margin-bottom: 2rem;
            animation: fadeIn 1.2s ease;
        }

        .hero-text p {
            font-size: 1.2rem;
            line-height: 1.8;
            color: var(--text-secondary);
            margin-bottom: 2rem;
            animation: fadeIn 1.4s ease;
        }

        .cta-buttons {
            display: flex;
            gap: 1rem;
            animation: fadeIn 1.6s ease;
        }

        .btn {
            padding: 1rem 2rem;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: var(--transition);
            border: 2px solid var(--accent);
        }

        .btn-primary {
            background: var(--accent);
            color: var(--bg-primary);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px var(--accent-glow);
        }

        .btn-secondary {
            background: transparent;
            color: var(--accent);
        }

        .btn-secondary:hover {
            background: var(--accent);
            color: var(--bg-primary);
            transform: translateY(-3px);
        }

        .hero-image {
            position: relative;
            animation: fadeIn 1.8s ease;
        }

        .code-window {
            background: var(--bg-secondary);
            border-radius: 15px;
            padding: 2rem;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            animation: float 4s ease-in-out infinite;
        }

        .window-header {
            display: flex;
            gap: 0.5rem;
            margin-bottom: 1rem;
        }

        .window-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
        }

        .dot-red { background: #ff5f56; }
        .dot-yellow { background: #ffbd2e; }
        .dot-green { background: #27c93f; }

        .code-content {
            font-family: 'Courier New', monospace;
            color: var(--text-secondary);
            line-height: 1.8;
        }

        .code-line {
            display: block;
            padding: 0.2rem 0;
        }

        .keyword { color: #ff79c6; }
        .function { color: #50fa7b; }
        .string { color: #f1fa8c; }

        /* Skills Section */
        .section {
            padding: 6rem 5%;
            position: relative;
            z-index: 1;
        }

        .section-title {
            text-align: center;
            font-size: 3rem;
            margin-bottom: 4rem;
            background: linear-gradient(135deg, var(--accent), #00aaff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            max-width: 1400px;
            margin: 0 auto;
        }

        .skill-card {
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 20px;
            border: 2px solid transparent;
            transition: var(--transition);
            backdrop-filter: blur(10px);
        }

        .skill-card:hover {
            border-color: var(--accent);
            transform: translateY(-10px);
            box-shadow: 0 20px 40px var(--accent-glow);
        }

        .skill-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .skill-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--accent);
        }

        .skill-bar {
            background: var(--bg-secondary);
            height: 8px;
            border-radius: 10px;
            overflow: hidden;
            margin-top: 1rem;
        }

        .skill-progress {
            height: 100%;
            background: linear-gradient(90deg, var(--accent), #00aaff);
            border-radius: 10px;
            transition: width 1s ease;
        }

        /* Projects Section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 3rem;
            max-width: 1400px;
            margin: 0 auto;
        }

        .project-card {
            background: var(--card-bg);
            border-radius: 20px;
            overflow: hidden;
            border: 2px solid transparent;
            transition: var(--transition);
            backdrop-filter: blur(10px);
        }

        .project-card:hover {
            border-color: var(--accent);
            transform: translateY(-10px) scale(1.02);
            box-shadow: 0 20px 60px var(--accent-glow);
        }

        .project-image {
            width: 100%;
            height: 250px;
            background: linear-gradient(135deg, var(--accent), #00aaff);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            position: relative;
            overflow: hidden;
        }

        .project-image::before {
            content: '';
            position: absolute;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            animation: shine 3s infinite;
        }

        @keyframes shine {
            0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
            100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }

        .project-info {
            padding: 2rem;
        }

        .project-info h3 {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            color: var(--accent);
        }

        .project-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .tag {
            background: var(--accent);
            color: var(--bg-primary);
            padding: 0.4rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
        }

        /* Contact Section */
        .contact-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 3rem;
            flex-wrap: wrap;
        }

        .contact-link {
            display: flex;
            align-items: center;
            gap: 1rem;
            padding: 1.5rem 2rem;
            background: var(--card-bg);
            border-radius: 15px;
            text-decoration: none;
            color: var(--text-primary);
            border: 2px solid transparent;
            transition: var(--transition);
        }

        .contact-link:hover {
            border-color: var(--accent);
            transform: translateY(-5px);
            box-shadow: 0 10px 30px var(--accent-glow);
        }

        .contact-icon {
            font-size: 2rem;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 2rem;
            background: var(--bg-secondary);
            color: var(--text-secondary);
            position: relative;
            z-index: 1;
        }

        /* Responsive */
        @media (max-width: 968px) {
            .hero-content {
                grid-template-columns: 1fr;
                text-align: center;
            }

            .hero-text h1 {
                font-size: 3rem;
            }

            .hero-text h2 {
                font-size: 1.5rem;
            }

            .cta-buttons {
                justify-content: center;
            }

            .nav-links {
                display: none;
            }

            .section-title {
                font-size: 2rem;
            }

            .projects-grid {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            .hero-text h1 {
                font-size: 2rem;
            }

            .hero-text h2 {
                font-size: 1.2rem;
            }

            .btn {
                padding: 0.8rem 1.5rem;
                font-size: 0.9rem;
            }

            .skills-grid {
                grid-template-columns: 1fr;
            }
        }

        /* Scroll animations */
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <div class="particles" id="particles"></div>

    <header>
        <nav>
            <a href="#" class="logo">FP</a>
            <ul class="nav-links">
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#competences">Compétences</a></li>
                <li><a href="#projets">Projets</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <button class="theme-toggle" onclick="toggleTheme()">☀️ Mode</button>
        </nav>
    </header>

    <section class="hero" id="accueil">
        <div class="hero-content">
            <div class="hero-text">
                <h1>Florian Prud'homme</h1>
                <h2>Développeur Fullstack En Recherche d'Alternance</h2>
                <p>Étudiant en 3ème année de Licence Informatique à l'École-IT, passionné par le développement web et mobile. Je recherche une alternance pour mettre en pratique mes compétences et contribuer à des projets innovants.</p>
                <div class="cta-buttons">
                    <a href="#projets" class="btn btn-primary">Voir mes projets</a>
                    <a href="#contact" class="btn btn-secondary">Me contacter</a>
                </div>
            </div>
            <div class="hero-image">
                <div class="code-window">
                    <div class="window-header">
                        <div class="window-dot dot-red"></div>
                        <div class="window-dot dot-yellow"></div>
                        <div class="window-dot dot-green"></div>
                    </div>
                    <div class="code-content">
                        <span class="code-line"><span class="keyword">const</span> <span class="function">developer</span> = {</span>
                        <span class="code-line">  name: <span class="string">"Florian Prud'homme"</span>,</span>
                        <span class="code-line">  level: <span class="string">"Licence 3"</span>,</span>
                        <span class="code-line">  stack: [<span class="string">"Frontend"</span>, <span class="string">"Backend"</span>],</span>
                        <span class="code-line">  motivation: <span class="string">"100%"</span>,</span>
                        <span class="code-line">  disponible: <span class="keyword">true</span></span>
                        <span class="code-line">};</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="competences">
        <h2 class="section-title fade-in">Compétences</h2>
        <div class="skills-grid">
            <div class="skill-card fade-in">
                <div class="skill-icon">🎨</div>
                <h3>Frontend</h3>
                <p>HTML, CSS, JavaScript, React</p>
                <div class="skill-bar">
                    <div class="skill-progress" style="width: 85%"></div>
                </div>
            </div>
            <div class="skill-card fade-in">
                <div class="skill-icon">⚙️</div>
                <h3>Backend</h3>
                <p>Node.js, PHP, Python, REST API, Java, Symfony</p>
                <div class="skill-bar">
                    <div class="skill-progress" style="width: 80%"></div>
                </div>
            </div>
            <div class="skill-card fade-in">
                <div class="skill-icon">💾</div>
                <h3>Bases de données</h3>
                <p>MySQL, PostgreSQL, MongoDB</p>
                <div class="skill-bar">
                    <div class="skill-progress" style="width: 75%"></div>
                </div>
            </div>
            <div class="skill-card fade-in">
                <div class="skill-icon">🔧</div>
                <h3>DevOps</h3>
                <p>Git, Docker, CI/CD, Linux, Windows Server</p>
                <div class="skill-bar">
                    <div class="skill-progress" style="width: 70%"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Nouvelle section Formation -->
    <section class="section" id="formation">
        <h2 class="section-title fade-in">Formation</h2>
        <div class="skills-grid">
            <div class="skill-card fade-in">
                <div class="skill-icon">🎓</div>
                <h3>Licence 3ᵉ année en cours d'obtention</h3>
                <p>École-IT</p>
            </div>
            <div class="skill-card fade-in">
                <div class="skill-icon">💻</div>
                <h3>BTS SIO - Option SLAM</h3>
                <p>Lycée Henri Wallon</p>
            </div>
            <div class="skill-card fade-in">
                <div class="skill-icon">📘</div>
                <h3>Baccalauréat - Options NSI et LLCE</h3>
                <p>Lycée Notre Dame Des Anges</p>
            </div>
        </div>
    </section>

    <section class="section" id="projets">
        <h2 class="section-title fade-in">Projets Réalisés</h2>
        <div class="projects-grid">
            <div class="project-card fade-in">
                <div class="project-image">⚖️</div>
                <div class="project-info">
                    <h3>Site Web Commissaire de Justice</h3>
                    <p>Refonte graphique complète du site web d'un Commissaire de Justice avec une interface moderne et responsive.</p>
                    <div class="project-tags">
                        <span class="tag">HTML</span>
                        <span class="tag">CSS</span>
                        <span class="tag">JavaScript</span>
                        <span class="tag">Responsive</span>
                    </div>
                    <br>
                    <h2>Mai - Juin 2023</h2>
                </div>
            </div>
            <div class="project-card fade-in">
                <div class="project-image">💅</div>
                <div class="project-info">
                    <h3>Site Web Institut Dalia</h3>
                    <p>Création d'un site web élégant pour un institut de beauté avec système de réservation et galerie photos.</p>
                    <div class="project-tags">
                        <span class="tag">HTML</span>
                        <span class="tag">CSS</span>
                        <span class="tag">PHP</span>
                        <span class="tag">Responsive</span>
                    </div>
                    <br>
                    <h2>Janvier - Février 2024</h2>
                </div>
            </div>
            <div class="project-card fade-in">
                <div class="project-image">🌐</div>
                <div class="project-info">
                    <h3>Site Web Portfolio</h3>
                    <p>Création d'un site portfolio dynamique avec un mode clair/sombre et une interface utilisateur moderne et agréable.</p>
                    <div class="project-tags">
                        <span class="tag">HTML</span>
                        <span class="tag">CSS</span>
                        <span class="tag">JavaScript</span>
                    </div>
                    <br>
                    <h2>Octobre 2025</h2>
                </div>
            </div>
        </div>
    </section>

    <section class="section" id="contact">
        <h2 class="section-title fade-in">Contact</h2>
        <div class="contact-content fade-in">
            <p style="font-size: 1.3rem; margin-bottom: 2rem;">Intéressé par mon profil ? N'hésitez pas à me contacter !</p>
            <div class="contact-links">
                <a href="mailto:flo.prudhomme59@gmail.com" class="contact-link">
                    <span class="contact-icon">📧</span>
                    <div>
                        <strong>Email</strong>
                        <p>flo.prudhomme59@gmail.com</p>
                    </div>
                </a>
                    <a href="https://www.linkedin.com/in/florian-prud-homme-2b3928261/" class="contact-link" target="_blank">
                        <span class="contact-icon">
                            <!-- Logo LinkedIn -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.024-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.352V9h3.414v1.561h.049c.477-.9 1.637-1.852 3.37-1.852 3.603 0 4.27 2.373 4.27 5.455v6.288zM5.337 7.433a2.062 2.062 0 1 1 0-4.125 2.062 2.062 0 0 1 0 4.125zM6.814 20.452H3.861V9h2.953v11.452zM22.225 0H1.771C.792 0 0 .771 0 1.725v20.549C0 23.23.792 24 1.771 24h20.451C23.205 24 24 23.23 24 22.274V1.725C24 .771 23.205 0 22.225 0z"/>
                            </svg>
                        </span>
                        <div>
                            <strong>LinkedIn</strong>
                        </div>
                    </a>

                    <a href="https://github.com/Flo1320" class="contact-link" target="_blank">
                        <span class="contact-icon">
                            <!-- Logo GitHub -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 .297a12 12 0 0 0-3.79 23.39c.6.111.82-.258.82-.577 0-.285-.011-1.04-.017-2.04-3.338.726-4.042-1.61-4.042-1.61-.547-1.389-1.337-1.759-1.337-1.759-1.09-.745.083-.729.083-.729 1.205.085 1.84 1.236 1.84 1.236 1.07 1.834 2.809 1.304 3.495.997.108-.775.42-1.304.763-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.382 1.236-3.22-.124-.304-.536-1.527.118-3.176 0 0 1.008-.322 3.3 1.23a11.52 11.52 0 0 1 3.004-.404 11.49 11.49 0 0 1 3.004.404c2.29-1.552 3.296-1.23 3.296-1.23.656 1.649.244 2.872.12 3.176.77.838 1.235 1.909 1.235 3.22 0 4.61-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222 0 1.606-.015 2.898-.015 3.293 0 .321.216.694.825.576A12.004 12.004 0 0 0 12 .297z"/>
                            </svg>
                        </span>
                        <div>
                            <strong>GitHub</strong>
                        </div>
                    </a>
                </a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy;  2025 Florian Prud'homme • Tous droits réservés</p>
    </footer>

    <script>
        // Theme Toggle
        function toggleTheme() {
            const body = document.body;
            const currentTheme = body.getAttribute('data-theme');
            const newTheme = currentTheme === 'light' ? 'dark' : 'light';
            body.setAttribute('data-theme', newTheme);
            
            const btn = document.querySelector('.theme-toggle');
            btn.textContent = newTheme === 'light' ? '🌙 Mode' : '☀️ Mode';
        }

        // Particles
        const particlesContainer = document.getElementById('particles');
        for (let i = 0; i < 50; i++) {
            const particle = document.createElement('div');
            particle.className = 'particle';
            particle.style.left = Math.random() * 100 + '%';
            particle.style.top = Math.random() * 100 + '%';
            particle.style.animationDelay = Math.random() * 6 + 's';
            particle.style.animationDuration = (Math.random() * 4 + 4) + 's';
            particlesContainer.appendChild(particle);
        }

        // Scroll animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));

        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });

        // Animate skill bars on scroll
        const skillBars = document.querySelectorAll('.skill-progress');
        const skillObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    const width = entry.target.style.width;
                    entry.target.style.width = '0';
                    setTimeout(() => {
                        entry.target.style.width = width;
                    }, 200);
                }
            });
        }, { threshold: 0.5 });

        skillBars.forEach(bar => skillObserver.observe(bar));
    </script>
</body>
</html>
