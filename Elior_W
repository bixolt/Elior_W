<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elior Oz - Software Engineer & Entrepreneur</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1e1e1e, #121212);
            color: #f5f5f5;
            overflow-x: hidden;
            scroll-behavior: smooth;
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
            position: relative;
        }

        /* Loading Screen */
        .loading {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 9999;
        }

        .loading video {
            width: 100px;
            height: 100px;
            object-fit: cover;
        }

        header {
            background: rgba(0, 0, 0, 0.9);
            color: #fff;
            padding: 2rem 0;
            text-align: center;
            position: relative;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            z-index: 10;
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
            color: #ffd700;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.5);
            animation: assemble 3s forwards;
        }

        @keyframes assemble {
            0% {
                opacity: 0;
                transform: translateZ(100px) rotateY(90deg);
            }
            50% {
                opacity: 0.5;
                transform: translateZ(50px) rotateY(45deg);
            }
            100% {
                opacity: 1;
                transform: translateZ(0) rotateY(0);
            }
        }

        nav {
            display: flex;
            justify-content: center;
            background: rgba(0, 0, 0, 0.8);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 2px solid #ffd700;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }

        nav a {
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            transition: all 0.3s ease;
            position: relative;
        }

        nav a::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 100%;
            height: 2px;
            background: #ffd700;
            transform: scaleX(0);
            transition: transform 0.3s ease;
            transform-origin: bottom right;
        }

        nav a:hover::after {
            transform: scaleX(1);
            transform-origin: bottom left;
        }

        .container {
            padding: 1rem;
            margin: 2rem auto;
            max-width: 900px;
            position: relative;
            z-index: 10;
        }

        section {
            padding: 2rem;
            margin: 2rem auto;
            max-width: 100%;
            background: rgba(25, 25, 25, 0.9);
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            opacity: 0;
            transform: translateY(50px);
            transition: opacity 1s ease, transform 1s ease;
        }

        section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .fade-in {
            opacity: 0;
            animation: fadeIn 1.5s forwards;
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }

        .zoom-in {
            transform: scale(0.8);
            animation: zoomIn 1s forwards;
        }

        @keyframes zoomIn {
            to {
                transform: scale(1);
            }
        }

        .slide-left {
            transform: translateX(30px);
            animation: slideLeft 1s forwards;
        }

        @keyframes slideLeft {
            to {
                transform: translateX(0);
            }
        }

        .slide-right {
            transform: translateX(-30px);
            animation: slideRight 1s forwards;
        }

        @keyframes slideRight {
            to {
                transform: translateX(0);
            }
        }

        .parallax {
            background-image: url('https://images.pexels.com/photos/1181240/pexels-photo-1181240.jpeg');
            height: 300px;
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
            margin-bottom: 2rem;
        }

        .parallax h2 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: #fff;
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            opacity: 0;
            animation: fadeInUp 1s forwards 0.5s;
        }

        @keyframes gradientBG {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .particles {
            position: fixed;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            z-index: 0;
            pointer-events: none;
        }

        .particle {
            position: absolute;
            width: 6px;
            height: 6px;
            background: #ffd700;
            border-radius: 50%;
            animation: particle 20s linear infinite;
        }

        @keyframes particle {
            0% {
                transform: translateY(0) translateX(0) scale(1);
            }
            100% {
                transform: translateY(-2000px) translateX(300px) scale(0);
            }
        }

        .highlight {
            color: #ffd700;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.5);
        }

        .slide-in {
            animation: slideIn 1s ease-out forwards;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .contact {
            background: rgba(25, 25, 25, 0.9);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            margin: 2rem auto;
            max-width: 900px;
            text-align: center;
        }

        .contact h2 {
            margin-top: 0;
        }

        .contact p {
            margin: 0.5rem 0;
        }

        .contact a {
            color: #ffd700;
            text-decoration: none;
            font-weight: bold;
        }

        .contact a:hover {
            text-decoration: underline;
        }

        .dedication {
            background: rgba(25, 25, 25, 0.9);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            margin: 2rem auto;
            max-width: 900px;
            text-align: center;
        }

        .dedication h2 {
            margin-top: 0;
        }

        /* Dynamic Elements */
        .dynamic-element {
            position: fixed;
            width: 20px;
            height: 20px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 50%;
            top: -50px;
            left: 50%;
            transform: translateX(-50%);
            opacity: 0;
            transition: all 1s ease;
        }

        .dynamic-element.visible {
            top: calc(50vh - 10px);
            opacity: 1;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            nav {
                flex-direction: column;
            }

            nav a {
                padding: 0.5rem;
                font-size: 0.9rem;
            }

            .container {
                padding: 1rem;
                margin: 1rem auto;
            }

            .parallax {
                height: 200px;
            }

            .parallax h2 {
                font-size: 1.5rem;
            }

            section {
                padding: 1rem;
                margin: 1rem auto;
            }

            .contact, .dedication {
                padding: 1rem;
                margin: 1rem auto;
            }
        }
    </style>
</head>
<body>
    <div class="loading">
        <video src="loading.mp4" autoplay muted loop></video>
    </div>
    <header>
        <h1>Elior Oz</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#experience">Experience</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#courses">Courses & Knowledge</a>
        <a href="#languages">Languages</a>
        <a href="#dedication">Dedication</a>
    </nav>
    <div class="container">
        <section id="about" class="slide-in visible">
            <h2 class="highlight">About Me</h2>
            <p class="fade-in">Hello! I'm Elior Oz, a passionate software engineer and entrepreneur. My journey in the tech world has been driven by a deep fascination with computer science and a desire to create innovative solutions. With years of experience in programming and project management, I am dedicated to exploring new technologies and pushing the boundaries of what's possible. I am always eager to take on new challenges and contribute to the advancement of the tech industry.</p>
            <div class="contact fade-in">
                <h2>Contact Information</h2>
                <p>Phone: <a href="tel:+0527857452">052-7857452</a></p>
                <p>Email: <a href="mailto:zdaci99@gmail.com">zdaci99@gmail.com</a></p>
            </div>
        </section>
        <section id="experience" class="slide-in visible">
            <h2 class="highlight">Experience</h2>
            <p class="zoom-in"><strong>ShortBlock:</strong> I developed a versatile code management tool named ShortBlock, featuring a unique programming language and specialized functionalities. This tool, entirely self-created, offers dynamic functionality and a user-friendly interface to streamline code management. Explore the project on <a href="https://github.com/bixolt/shortBlock" target="_blank">GitHub</a>.</p>
            <p class="zoom-in"><strong>Banda:</strong> As the CEO, I built the Banda website from scratch and significantly contributed to its development. Banda is a software library aimed at enhancing development practices. Check out the Banda project on <a href="https://github.com/bixolt/BANDA" target="_blank">GitHub</a>.</p>
            <p class="zoom-in"><strong>LinkedIn Programming School:</strong> I regularly post programming lessons and AI tips on my LinkedIn profile, offering valuable insights and guidance to the community. Visit my profile for more details: <a href="https://www.linkedin.com/in/banda-elior-440208208/" target="_blank">LinkedIn</a>.</p>
            <p class="zoom-in"><strong>Theories and Projects:</strong> I have developed numerous theories in areas such as neuroscience, object-oriented programming (OOP), and AI algorithms. My work includes various projects in the early stages, such as the Extora Partner Platform, Sports and Human Body Platform, Advanced Graph Algorithms in Python, and a sophisticated categorization system.</p>
        </section>
        <section id="skills" class="slide-in visible">
            <h2 class="highlight">Skills</h2>
            <ul class="slide-left">
                <li>Advanced proficiency in programming languages: JavaScript, Python, Java, C++</li>
                <li>Extensive experience with software development frameworks and tools</li>
                <li>Deep understanding of data structures, algorithms, and system architecture</li>
                <li>Proficiency in creating and managing dynamic and static data structures</li>
                <li>Strong skills in project management and software lifecycle</li>
                <li>Expertise in developing and managing open-source projects</li>
            </ul>
        </section>
        <section id="projects" class="slide-in visible">
            <h2 class="highlight">Projects</h2>
            <h3>Completed Projects</h3>
            <ul class="slide-right">
                <li><strong>ShortBlock:</strong> A versatile code management tool with dynamic functionality and a user-friendly design, created entirely by myself.</li>
                <li><strong>LinkedIn Programming School:</strong> A comprehensive platform offering programming lessons and tips on artificial intelligence, available on my LinkedIn profile.</li>
            </ul>
            <h3>Ongoing Projects</h3>
            <ul class="slide-right">
                <li><strong>Extora Partner Platform:</strong> A partner platform designed to enhance business processes and integrations.</li>
                <li><strong>Sports and Human Body Platform:</strong> A sophisticated platform focused on sports and human body analytics.</li>
                <li><strong>Advanced Graph Algorithms in Python:</strong> A project exploring complex graph algorithms implemented in Python.</li>
                <li><strong>Categorization System:</strong> A system under development for advanced categorization and management of data.</li>
            </ul>
        </section>
        <section id="courses" class="slide-in visible">
            <h2 class="highlight">Courses & Knowledge</h2>
            <ul class="slide-left">
                <li>AI Algorithms</li>
                <li>Full-Stack Engineering</li>
                <li>Physics</li>
                <li>Mathematics</li>
                <li>Python</li>
                <li>C#</li>
                <li>JavaScript</li>
                <li>Java</li>
                <li>SQL</li>
                <li>Networks</li>
                <li>Data Structures</li>
                <li>Creative Thinking</li>
                <li>Exploiting Weaknesses</li>
            </ul>
        </section>
        <section id="languages" class="slide-in visible">
            <h2 class="highlight">Languages</h2>
            <ul class="slide-right">
                <li>Hebrew (Native)</li>
                <li>English (Fluent)</li>
            </ul>
        </section>
        <section id="dedication" class="slide-in visible dedication">
            <h2 class="highlight">Why You Should Choose Me</h2>
            <p class="fade-in">With extensive experience in programming and entrepreneurship, I possess a deep understanding of technology and its potential. My work on various projects, including ShortBlock and Banda, demonstrates my ability to develop innovative solutions and manage complex software systems. My commitment to open source and continuous improvement reflects my dedication to making meaningful contributions to the field of computer science. Choosing me means bringing onboard a passionate, skilled, and proactive software engineer ready to tackle new challenges and drive your projects to success.</p>
        </section>
        <section class="dedication">
            <h2 class="highlight">Dedication to the Client</h2>
            <p class="fade-in">Thank you for the opportunity to introduce myself. With deep experience in the tech field, I am excited to be part of this progressive industry. My goal is to engage in the field, develop innovative solutions, and explore the limits of existing knowledge. Over my career, I have led significant projects and created unique contributions, and I aspire to continue influencing the industry with new insights and ideas. Thank you for believing in me and my skills.</p>
        </section>
    </div>
    <div class="particles"></div>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const sections = document.querySelectorAll('section');
            const options = {
                threshold: 0.2
            };

            const observer = new IntersectionObserver(function(entries, observer) {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                        addDynamicElement(entry.target);
                    }
                });
            }, options);

            sections.forEach(section => {
                observer.observe(section);
            });

            // Hide the loading screen once the content is fully loaded
            window.addEventListener('load', function() {
                document.querySelector('.loading').style.display = 'none';
            });
        });

        function createParticles(color) {
            const container = document.createElement('div');
            container.classList.add('particles');
            document.body.appendChild(container);

            for (let i = 0; i < 100; i++) {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                particle.style.left = Math.random() * 100 + 'vw';
                particle.style.top = Math.random() * 100 + 'vh';
                particle.style.background = color;
                particle.style.animationDelay = Math.random() * 10 + 's';
                container.appendChild(particle);
            }
        }

        const colors = ['#00eaff', '#ffd700', '#33ff57', '#ff33a8'];
        let colorIndex = 0;

        // Initial particles
        createParticles(colors[colorIndex]);

        // Smooth scrolling for navigation links and change particle color
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });

                // Remove existing particles
                document.querySelectorAll('.particles').forEach(p => p.remove());

                // Update color index and create new particles
                colorIndex = (colorIndex + 1) % colors.length;
                createParticles(colors[colorIndex]);
            });
        });

        function addDynamicElement(target) {
            const dynamicElement = document.createElement('div');
            dynamicElement.classList.add('dynamic-element');
            target.appendChild(dynamicElement);

            setTimeout(() => {
                dynamicElement.classList.add('visible');
            }, 100);
        }
    </script>
</body>
</html>
