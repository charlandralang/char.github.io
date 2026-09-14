# char.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | PhD Student in Human-Centered Computing</title>
    <style>
        :root {
            --bg-color: #ffffff;
            --text-color: #222222;
            --link-color: #0066cc;
            --accent-muted: #666666;
            --border-color: #eeeeee;
            --font-stack: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        /* Minimalist Reset & Global Styles */
        body {
            font-family: var(--font-stack);
            color: var(--text-color);
            background-color: var(--bg-color);
            line-height: 1.6;
            max-width: 750px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        a {
            color: var(--link-color);
            text-decoration: none;
        }

        a:hover, a:focus {
            text-decoration: underline;
        }

        h1, h2, h3 {
            font-weight: 600;
            line-height: 1.2;
            margin-top: 2rem;
            margin-bottom: 0.5rem;
        }

        section {
            margin-bottom: 2.5rem;
        }

        /* Two-Column Header Layout */
        .profile-header {
            display: flex;
            align-items: center;
            gap: 2rem;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 2rem;
            margin-bottom: 2rem;
        }

        .profile-pic {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            background-color: #f0f0f0; /* Fallback before image loads */
        }

        .profile-info h1 {
            margin: 0 0 0.25rem 0;
            font-size: 2.2rem;
        }

        .affiliation {
            font-size: 1.1rem;
            color: var(--accent-muted);
            margin: 0 0 1rem 0;
        }

        .links-list {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        /* Lists formatting */
        ul {
            padding-left: 1.25rem;
            margin-top: 0.5rem;
        }

        li {
            margin-bottom: 0.5rem;
        }

        .news-date, .pub-venue {
            font-weight: bold;
            color: var(--accent-muted);
            margin-right: 0.5rem;
        }

        .me {
            text-decoration: underline;
            font-weight: 600;
        }

        /* Responsive design adjustments */
        @media (max-width: 600px) {
            .profile-header {
                flex-direction: column;
                text-align: center;
                gap: 1rem;
            }
            .links-list {
                justify-content: center;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header class="profile-header">
        <!-- Replace with your actual headshot file name, e.g., "avatar.jpg" -->
        <img class="profile-pic" src="data:image/svg+xml;utf8,<svg xmlns='http://w3.org' width='140' height='140' viewBox='0 0 140 140'><rect width='140' height='140' fill='%23eee'/><text x='50%25' y='50%25' dominant-baseline='middle' text-anchor='middle' font-family='sans-serif' font-size='14' fill='%23666'>Headshot</text></svg>" alt="Your Name profile picture">
        
        <div class="profile-info">
            <h1>Your Name</h1>
            <p class="affiliation">PhD Student in Human-Centered Computing<br>Your University</p>
            <nav aria-label="Social and academic links">
                <ul class="links-list">
                    <li><a href="mailto:your.email@university.edu">Email</a></li>
                    <li><a href="https://google.com" target="_blank" rel="noopener">Google Scholar</a></li>
                    <li><a href="https://github.com" target="_blank" rel="noopener">GitHub</a></li>
                    <li><a href="https://linkedin.com" target="_blank" rel="noopener">LinkedIn</a></li>
                    <li><a href="cv.pdf" target="_blank">CV (PDF)</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <!-- About Me Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>I am a PhD student in the Human-Centered Computing program at Your University, advised by Dr. Faculty Member. My research sits at the intersection of Human-Computer Interaction (HCI) and digital accessibility. Specifically, I study how to build highly accessible, semantic systems that empower marginalized communities to interact fluidly with intelligent web technologies.</p>
        </section>

        <!-- Research Interests Section -->
        <section id="interests">
            <h2>Research Interests</h2>
            <ul>
                <li><strong>Human-Computer Interaction (HCI):</strong> User-centered system design and qualitative evaluation.</li>
                <li><strong>Digital Accessibility:</strong> Evaluating assistive technologies and automated repair systems.</li>
                <li><strong>Human-AI Interaction:</strong> Ensuring equitable outcomes in conversational interfaces.</li>
            </ul>
        </section>

        <!-- News Section -->
        <section id="news">
            <h2>News</h2>
            <ul>
                <li><span class="news-date">Sep 2026:</span> Started my PhD journey in the HCC department!</li>
                <li><span class="news-date">Aug 2026:</span> Relocated and set up office space at the lab.</li>
            </ul>
        </section>

        <!-- Publications Section -->
        <section id="publications">
            <h2>Publications</h2>
            
            <h3>2026</h3>
            <ul>
                <li>
                    "Title of Your Outstanding Conference or Workshop Paper." <br>
                    <span class="me">Your Name</span>, Second Author, and Third Author. <br>
                    <span class="pub-venue">CHI WORKSHOP '26</span> — <a href="#">[PDF]</a> <a href="#">[Project Page]</a>
                </li>
            </ul>
        </section>
    </main>

    <footer>
        <p style="font-size: 0.85rem; color: var(--accent-muted); border-top: 1px solid var(--border-color); padding-top: 1.5rem; margin-top: 4rem;">
            &copy; 2026 Your Name. Built with minimal, accessible HTML &amp; CSS.
        </p>
    </footer>

</body>
</html>
