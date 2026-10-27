
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mimi's Little Corner 🎀</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <header class="navbar">
        <a href="#home" class="logo">mimi<span>.</span></a>

        <button class="menu-btn" id="menuBtn" aria-label="Toggle menu">
            ☰
        </button>

        <nav id="navMenu">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact" class="nav-contact">Say hello ♡</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-text">
            <div class="small-tag">✿ welcome to my little world</div>

            <h1>
                Creating little<br>
                things with <span>love.</span>
            </h1>

            <p>
                Hi, I'm Mimi! A creative soul learning web development
                and turning little ideas into beautiful digital experiences.
            </p>

            <div class="hero-buttons">
                <a href="#projects" class="btn primary">Explore my work ↗</a>
                <a href="#about" class="btn secondary">Get to know me</a>
            </div>

            <div class="hero-note" hidden>
                ♡ Currently learning HTML, CSS & JavaScript
            </div>
        </div>

        <div class="hero-visual">
            <div class="pink-circle">
                <div class="profile-card">
                    <div class="profile-emoji">🌷</div>
                    <h3>Little things,<br>big dreams.</h3>
                    <p>Made with love & a little bit of magic ✨</p>
                </div>
            </div>

            <div class="floating-star star-one">✦</div>
            <div class="floating-star star-two">♡</div>
            <div class="floating-star star-three">✿</div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section about" id="about">
        <div class="section-heading">
            <span class="eyebrow">A LITTLE ABOUT ME</span>
            <h2>Just a girl with <span>big dreams.</span></h2>
        </div>

        <div class="about-card">
            <div class="about-emoji">☁️</div>

            <div>
                <h3>Hello, lovely human!</h3>

                <p>
                    I'm a beginner web developer who loves creating
                    beautiful websites. I'm passionate about learning,
                    exploring new ideas, and making the internet
                    a little more lovely.
                </p>

                <p>
                    When I'm not coding, you'll probably find me
                    listening to music, drinking coffee, or dreaming
                    about my next creative project.
                </p>

                <div class="about-signature">With love, Mimi ♡</div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="section skills" id="skills">
        <div class="section-heading">
            <span class="eyebrow">MY LITTLE TOOLBOX</span>
            <h2>Things I'm <span>learning.</span></h2>
        </div>

        <div class="skill-grid">
            <div class="skill-card">
                <div class="skill-icon">🌸</div>
                <h3>HTML</h3>
                <p>Building the structure of beautiful websites.</p>
            </div>

            <div class="skill-card">
                <div class="skill-icon">🎨</div>
                <h3>CSS</h3>
                <p>Making everything look pretty and polished.</p>
            </div>

            <div class="skill-card">
                <div class="skill-icon">✨</div>
                <h3>JavaScript</h3>
                <p>Adding magic and interaction to my pages.</p>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section projects" id="projects">
        <div class="section-heading">
            <span class="eyebrow">A FEW LITTLE CREATIONS</span>
            <h2>My <span>projects.</span></h2>
        </div>

        <div class="project-grid">
            <article class="project-card">
                <div class="project-image pink">
                    <span>🌷</span>
                </div>

                <div class="project-info">
                    <span class="project-type">HTML & CSS</span>
                    <h3>My Dreamy Portfolio</h3>
                    <p>A little corner of the internet that feels like me.</p>
                    <a href="#home">Explore project ↗</a>
                </div>
            </article>

            <article class="project-card">
                <div class="project-image lavender">
                    <span>☁️</span>
                </div>

                <div class="project-info">
                    <span class="project-type">COMING SOON</span>
                    <h3>Cloud Nine</h3>
                    <p>A dreamy little project filled with creativity.</p>
                    <a href="#contact">Stay tuned ♡</a>
                </div>
            </article>

            <article class="project-card">
                <div class="project-image peach">
                    <span>🍓</span>
                </div>

                <div class="project-info">
                    <span class="project-type">COMING SOON</span>
                    <h3>Berry Sweet</h3>
                    <p>A cute and colorful website idea in the making.</p>
                    <a href="#contact">Stay tuned ♡</a>
                </div>
            </article>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section contact" id="contact">
        <div class="contact-card">
            <div class="contact-flower">🌼</div>

            <span class="eyebrow">LET'S CONNECT</span>

            <h2>Have a little idea?</h2>

            <p>
                I'd love to hear from you! Let's create something
                beautiful together.
            </p>

            <a href="mailto:hello@example.com" class="btn primary">
                Say hello to me ♡
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Made with ♡ and a little bit of magic.</p>
        <p>© <span id="year"></span> Mimi's Little Corner</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
