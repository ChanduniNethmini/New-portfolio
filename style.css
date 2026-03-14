:root {
    --bg-color: #0d1117;
    --card-bg: #161b22;
    --text-primary: #f0f6fc;
    --text-secondary: #8b949e;
    --accent: #58a6ff;
    --accent-glow: rgba(88, 166, 255, 0.4);
    --gradient-1: linear-gradient(135deg, #FF6B6B 0%, #FEC163 100%);
    --gradient-2: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --glass: rgba(22, 27, 34, 0.7);
    --border: 1px solid rgba(240, 246, 252, 0.1);
    --font-heading: 'Outfit', sans-serif;
    --font-body: 'Outfit', sans-serif;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    background-color: var(--bg-color);
    color: var(--text-primary);
    font-family: var(--font-body);
    line-height: 1.6;
    overflow-x: hidden;
}

/* Custom Scrollbar */
::-webkit-scrollbar {
    width: 6px;
}
::-webkit-scrollbar-thumb {
    background: var(--text-secondary);
    border-radius: 4px;
}
::-webkit-scrollbar-track {
    background: var(--bg-color);
}

/* Cursor Effect */
.cursor-dot,
.cursor-outline {
    position: fixed;
    top: 0;
    left: 0;
    transform: translate(-50%, -50%);
    border-radius: 50%;
    z-index: 9999;
    pointer-events: none;
}
.cursor-dot {
    width: 8px;
    height: 8px;
    background-color: var(--accent);
}
.cursor-outline {
    width: 40px;
    height: 40px;
    border: 2px solid var(--accent);
    transition: all 0.2s ease-out;
}

/* Navbar */
.navbar {
    position: fixed;
    top: 0;
    width: 100%;
    padding: 1.5rem 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(13, 17, 23, 0.85);
    backdrop-filter: blur(10px);
    z-index: 1000;
    border-bottom: var(--border);
}

.logo {
    font-size: 1.8rem;
    font-weight: 700;
    background: var(--gradient-1); /* Use a gradient */
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    cursor: pointer;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 2.5rem;
}

.nav-links a {
    text-decoration: none;
    color: var(--text-secondary); /* Muted color initially */
    font-weight: 500;
    transition: color 0.3s ease;
    position: relative;
    font-size: 1rem;
}

.nav-links a:hover,
.nav-links a.active {
    color: var(--text-primary); /* Bright on hover */
}

/* Underline animation */
.nav-links a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: -4px;
    left: 0;
    background-color: var(--accent);
    transition: width 0.3s ease;
}

.nav-links a:hover::after {
    width: 100%;
}

.hamburger {
    display: none;
    cursor: pointer;
}

.hamburger span {
    display: block;
    width: 25px;
    height: 3px;
    background-color: var(--text-primary);
    margin: 5px 0;
    transition: 0.4s;
}

/* Hero Section */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center; /* Center horizontally */
    padding: 0 10%;
    position: relative;
    overflow: hidden;
    gap: 4rem; /* Add gap between content and visual */
    padding-top: 80px; /* Account for navbar */
    text-align: left; /* Reset text align */
}

/* Background Glows */
.hero::before {
    content: '';
    position: absolute;
    top: -10%;
    right: -10%;
    width: 600px;
    height: 600px;
    background: radial-gradient(circle, rgba(88, 166, 255, 0.15) 0%, transparent 70%);
    filter: blur(80px);
    z-index: -1;
}

.hero::after {
    content: '';
    position: absolute;
    bottom: -10%;
    left: -10%;
    width: 500px;
    height: 500px;
    background: radial-gradient(circle, rgba(255, 107, 107, 0.1) 0%, transparent 70%);
    filter: blur(80px);
    z-index: -1;
}

.hero-content {
    flex: 1;
    max-width: 600px;
    z-index: 2;
    animation: fadeUp 1s ease-out;
}

.greeting {
    font-size: 1.2rem;
    color: var(--accent);
    font-weight: 500;
    margin-bottom: 0.5rem;
    display: block;
}

.name {
    font-size: 4.5rem; /* Larger Name */
    font-weight: 800;
    line-height: 1.1;
    margin-bottom: 1rem;
    background: linear-gradient(to right, #fff, #a5b4fc);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    letter-spacing: -1px;
}

.role {
    font-size: 2rem;
    color: var(--text-secondary);
    margin-bottom: 1.5rem;
    font-weight: 400;
}

.role .highlight {
    color: var(--text-primary);
    font-weight: 600;
}

.summary {
    font-size: 1.1rem;
    color: var(--text-secondary);
    margin-bottom: 2.5rem;
    max-width: 500px;
    line-height: 1.8;
}

.cta-buttons {
    display: flex;
    gap: 1.5rem;
    margin-bottom: 3rem;
}

.btn {
    padding: 12px 32px;
    border-radius: 8px;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.3s ease;
    font-size: 1rem;
    position: relative;
    overflow: hidden;
}

.btn.primary {
    background: var(--accent); /* Solid accent color */
    color: #0d1117; /* Dark text for contrast */
    border: 2px solid var(--accent);
}

.btn.primary:hover {
    box-shadow: 0 0 20px var(--accent-glow);
    transform: translateY(-2px);
}

.btn.secondary {
    background: transparent;
    color: var(--text-primary);
    border: 1px solid var(--border);
}

.btn.secondary::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 0%;
    height: 100%;
    background: rgba(255, 255, 255, 0.05);
    transition: width 0.3s ease;
    z-index: -1;
}

.btn.secondary:hover {
    border-color: var(--text-primary);
    color: #fff;
}
.btn.secondary:hover::before {
    width: 100%;
}


.social-links {
    display: flex;
    gap: 1.5rem;
}

.social-links a {
    color: var(--text-secondary);
    font-size: 1.5rem;
    transition: all 0.3s ease;
}

.social-links a:hover {
    color: var(--accent);
    transform: translateY(-3px);
}

/* Hero Visual (Code Block) */
.hero-visual {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    perspective: 1000px;
    animation: float 6s ease-in-out infinite;
}

.code-block {
    background: #1e1e1e; /* VS Code dark bg roughly */
    border-radius: 12px;
    border: 1px solid #333;
    width: 100%;
    max-width: 500px;
    box-shadow: 0 20px 50px rgba(0,0,0,0.5);
    overflow: hidden;
    transform: rotateY(-5deg) rotateX(5deg);
    transition: transform 0.3s ease;
}

.hero-visual:hover .code-block {
    transform: rotateY(0deg) rotateX(0deg);
}

.code-header {
    background: #252526;
    padding: 10px 15px;
    display: flex;
    gap: 8px;
    border-bottom: 1px solid #333;
}

.dot {
    width: 12px;
    height: 12px;
    border-radius: 50%;
}

.red { background: #ff5f56; }
.yellow { background: #ffbd2e; }
.green { background: #27c93f; }

pre {
    padding: 20px;
    font-family: 'Fira Code', monospace;
    font-size: 0.95rem;
    color: #d4d4d4;
    overflow-x: auto;
}

.token.keyword { color: #569cd6; } /* Blue */
.token.string { color: #ce9178; } /* Orange/Brown */
.token.boolean { color: #569cd6; }
.token.function { color: #dcdcaa; } /* Yellow */

/* Keyframe Animations */
@keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-20px); }
}

@keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

/* Sections General */
.section {
    padding: 100px 0;
    position: relative;
    border-top: 1px solid rgba(255,255,255,0.02);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

.section-title {
    font-size: 2.5rem;
    margin-bottom: 4rem;
    text-align: center;
    position: relative;
    display: inline-block;
    left: 50%;
    transform: translateX(-50%);
}

.section-title::after {
    content: '';
    position: absolute;
    width: 60px;
    height: 4px;
    background: var(--accent);
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 2px;
}

/* Experience Timeline */
.timeline {
    position: relative;
    max-width: 800px;
    margin: 0 auto;
}

.timeline::before {
    content: '';
    position: absolute;
    left: 20px; /* Aligned left for mobile, check media query */
    top: 0;
    bottom: 0;
    width: 2px;
    background: var(--border);
}

.timeline-item {
    position: relative;
    padding-left: 60px;
    margin-bottom: 3rem;
}

.timeline-dot {
    position: absolute;
    left: 11px;
    top: 5px;
    width: 20px;
    height: 20px;
    background: var(--bg-color);
    border: 3px solid var(--accent);
    border-radius: 50%;
    z-index: 1;
    transition: background 0.3s;
}

.timeline-item:hover .timeline-dot {
    background: var(--accent);
}

.timeline-date {
    font-size: 0.9rem;
    color: var(--accent);
    margin-bottom: 0.5rem;
    font-weight: 500;
}

.timeline-content {
    background: var(--card-bg);
    padding: 1.5rem;
    border-radius: 12px;
    border: var(--border);
    transition: transform 0.3s ease;
}

.timeline-content:hover {
    transform: translateX(10px);
    border-color: var(--accent);
}

.timeline-content h3 {
    font-size: 1.3rem;
    margin-bottom: 0.3rem;
    color: var(--text-primary);
}

.timeline-content h4 {
    font-size: 1rem;
    color: var(--text-secondary);
    margin-bottom: 1rem;
    font-weight: 400;
}

/* Skills Grid */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
}

.skill-category {
    background: var(--card-bg);
    padding: 2rem;
    border-radius: 16px;
    border: var(--border);
    transition: transform 0.3s ease;
}

.skill-category:hover {
    transform: translateY(-5px);
    border-color: var(--text-secondary);
}

.skill-category h3 {
    margin-bottom: 1.5rem;
    color: var(--accent);
    font-size: 1.4rem;
    text-align: center;
}

.skill-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
    justify-content: center;
}

.skill-tags span {
    background: rgba(255, 255, 255, 0.05);
    padding: 6px 14px;
    border-radius: 20px;
    font-size: 0.9rem;
    border: 1px solid rgba(255, 255, 255, 0.1);
    transition: all 0.3s ease;
}

.skill-tags span:hover {
    background: var(--accent);
    color: #000;
    border-color: var(--accent);
}

/* Projects Grid */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 2.5rem;
}

.project-card {
    background: var(--card-bg);
    border-radius: 16px;
    overflow: hidden;
    border: var(--border);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
}

.project-image {
    height: 200px;
    width: 100%;
}

.project-info {
    padding: 1.5rem;
}

.project-info h3 {
    font-size: 1.4rem;
    margin-bottom: 0.8rem;
}

.project-info p {
    font-size: 0.95rem;
    color: var(--text-secondary);
    margin-bottom: 1.5rem;
    min-height: 3rem; /* Align cards */
}

.tech-stack {
    display: flex;
    gap: 0.8rem;
    margin-bottom: 1.5rem;
    font-size: 0.85rem;
}

.tech-stack span {
    color: var(--accent);
}

.project-links {
    display: flex;
    gap: 1rem;
}

.btn-sm {
    padding: 6px 16px;
    font-size: 0.9rem;
    border: 1px solid var(--border);
    border-radius: 6px;
    color: var(--text-primary);
    text-decoration: none;
    transition: all 0.3s;
}

.btn-sm:hover {
    background: var(--text-primary);
    color: var(--bg-color);
}

/* Certifications */
.cert-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 2rem;
}

.cert-card {
    background: linear-gradient(180deg, rgba(26, 32, 40, 0.9), rgba(22, 27, 34, 0.95));
    border: var(--border);
    border-radius: 16px;
    padding: 1.8rem;
    transition: transform 0.3s ease, border-color 0.3s ease;
    position: relative;
    overflow: hidden;
}

.cert-card::after {
    content: '';
    position: absolute;
    top: -50%;
    right: -30%;
    width: 220px;
    height: 220px;
    background: radial-gradient(circle, rgba(88, 166, 255, 0.15) 0%, transparent 70%);
    filter: blur(10px);
    opacity: 0.6;
}

.cert-card:hover {
    transform: translateY(-6px);
    border-color: var(--accent);
}

.cert-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem;
    position: relative;
    z-index: 1;
}

.cert-logo {
    width: 46px;
    height: 46px;
    border-radius: 12px;
    display: grid;
    place-items: center;
    background: rgba(255, 255, 255, 0.08);
    border: 1px solid rgba(255, 255, 255, 0.15);
    color: #e8f1ff;
    font-size: 1.2rem;
}

.cert-logo.cpp span {
    font-weight: 700;
    font-size: 0.9rem;
    letter-spacing: 0.3px;
}

.cert-logo.aws {
    background: rgba(255, 153, 0, 0.12);
    border-color: rgba(255, 153, 0, 0.35);
    color: #ffbf69;
}

.cert-logo.udemy {
    background: rgba(255, 255, 255, 0.1);
    border-color: rgba(255, 255, 255, 0.2);
}

.cert-logo.devops {
    background: rgba(0, 204, 255, 0.12);
    border-color: rgba(0, 204, 255, 0.35);
    color: #7bdfff;
}

.cert-pill-row {
    display: flex;
    align-items: center;
    gap: 0.8rem;
    margin-bottom: 0.6rem;
}

.cert-badge {
    padding: 4px 10px;
    border-radius: 999px;
    font-size: 0.75rem;
    background: rgba(88, 166, 255, 0.15);
    border: 1px solid rgba(88, 166, 255, 0.35);
    color: var(--accent);
    font-weight: 600;
    letter-spacing: 0.3px;
}

.cert-date {
    font-size: 0.85rem;
    color: var(--text-secondary);
}

.cert-card h3 {
    font-size: 1.2rem;
    margin-bottom: 0.4rem;
    position: relative;
    z-index: 1;
}

.cert-issuer {
    color: var(--text-secondary);
    font-size: 0.95rem;
    margin-bottom: 0.8rem;
    position: relative;
    z-index: 1;
}

.cert-desc {
    color: var(--text-secondary);
    font-size: 0.95rem;
    position: relative;
    z-index: 1;
}

.cert-actions {
    margin-top: 1.2rem;
    display: flex;
    gap: 0.8rem;
    position: relative;
    z-index: 1;
}

/* Publications */
.pubs-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2.5rem;
}

.pub-card {
    background: var(--card-bg);
    border: var(--border);
    border-radius: 16px;
    padding: 2rem;
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
}

.pub-card:hover {
    transform: translateY(-6px);
    border-color: var(--accent);
    box-shadow: 0 12px 30px rgba(0,0,0,0.25);
}

.pub-meta {
    display: flex;
    gap: 1rem;
    align-items: center;
    margin-bottom: 1rem;
}

.pub-type {
    padding: 4px 10px;
    border-radius: 8px;
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.6px;
    background: rgba(255, 107, 107, 0.15);
    border: 1px solid rgba(255, 107, 107, 0.35);
    color: #ffb4b4;
}

.pub-date {
    font-size: 0.85rem;
    color: var(--text-secondary);
}

.pub-venue {
    color: var(--text-secondary);
    font-size: 0.95rem;
    margin: 0.6rem 0 0.8rem;
}

.pub-desc {
    color: var(--text-secondary);
    font-size: 0.95rem;
    margin-bottom: 1.5rem;
}

.pub-actions {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
}


/* Contact Section */
.contact-content {
    display: grid;
    grid-template-columns: 1fr 1.5fr;
    gap: 4rem;
    align-items: center;
}

.contact-info {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    margin-top: 2rem;
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    font-size: 1.1rem;
    color: var(--text-secondary);
}

.contact-item i {
    color: var(--accent);
    font-size: 1.3rem;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 1.2rem;
    background: var(--card-bg);
    padding: 2.5rem;
    border-radius: 16px;
    border: var(--border);
}

.contact-form input,
.contact-form textarea {
    background: rgba(0, 0, 0, 0.2);
    border: 1px solid var(--border);
    padding: 14px;
    border-radius: 8px;
    color: var(--text-primary);
    font-family: inherit;
    font-size: 1rem;
    resize: none;
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: none;
    border-color: var(--accent);
}

/* Footer */
footer {
    text-align: center;
    padding: 3rem 0;
    color: var(--text-secondary);
    font-size: 0.9rem;
    border-top: var(--border);
    margin-top: 4rem;
}

/* Responsive */
@media (max-width: 900px) {
    .nav-links {
        display: none; /* Mobile menu needed */
    }
    .hamburger {
        display: block;
    }
    .hero {
        flex-direction: column-reverse; /* Visual on top? Or bottom? Let's stack */
        padding-top: 120px;
        text-align: center;
        gap: 2rem;
    }
    .hero pre {
        font-size: 0.8rem;
    }
    .greeting, .summary {
        margin: 0 auto;
        margin-bottom: 1rem;
    }
    .cta-buttons {
        justify-content: center;
    }
    .social-links {
        justify-content: center;
    }
    .hero-content {
        max-width: 100%;
    }
    .contact-content {
        grid-template-columns: 1fr;
    }
    .skills-grid {
        grid-template-columns: 1fr;
    }
}
