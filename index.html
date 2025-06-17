<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UNI - Investor Access</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-blue: #00aaff;
            --dark-bg: #0a0a0a;
            --dark-card: #101010;
            --glow-color: rgba(0, 170, 255, 0.5);
            --border-color: rgba(0, 170, 255, 0.2);
            --nav-height: 70px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: var(--dark-bg);
            color: #e0e0e0;
            overflow-x: hidden;
        }

        /* --- PASSWORD GATE STYLES --- */
        #password-gate {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background-color: var(--dark-bg);
            z-index: 9999;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: opacity 0.5s ease-out;
        }
        #password-gate.hidden {
            opacity: 0;
            pointer-events: none;
        }
        .gate-container {
            width: 90%;
            max-width: 500px;
            padding: 40px;
            text-align: center;
            background: rgba(16, 16, 16, 0.5);
            backdrop-filter: blur(10px);
            border: 1px solid var(--border-color);
            border-radius: 16px;
            box-shadow: 0 0 40px rgba(0,0,0,0.5);
        }
        .gate-container h1 {
            font-size: 2rem;
            color: var(--primary-blue);
            margin-bottom: 15px;
        }
        .gate-container p {
            color: #a0a0a0;
            margin-bottom: 30px;
            line-height: 1.6;
        }
        #password-input {
            width: 100%;
            padding: 15px;
            margin-bottom: 20px;
            background-color: rgba(0,0,0,0.3);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            color: #fff;
            font-size: 1rem;
            text-align: center;
        }
        #password-input:focus {
            outline: none;
            border-color: var(--primary-blue);
            box-shadow: 0 0 15px var(--glow-color);
        }
        .gate-button {
            width: 100%;
            padding: 15px;
            border: none;
            background: linear-gradient(45deg, var(--primary-blue), #0077b6);
            color: #fff;
            font-weight: 600;
            font-size: 1.1rem;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        .gate-button:hover {
            box-shadow: 0 0 20px var(--glow-color);
        }
        #error-message {
            color: #ff4d4d;
            margin-top: 15px;
            height: 20px;
            visibility: hidden;
        }
        .gate-container.shake {
            animation: shake 0.5s ease-in-out;
        }
        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            10%, 30%, 50%, 70%, 90% { transform: translateX(-10px); }
            20%, 40%, 60%, 80% { transform: translateX(10px); }
        }

        /* --- MAIN CONTENT --- */
        #main-content {
            visibility: hidden; 
            opacity: 0;
            transition: opacity 0.5s ease-in;
        }
        #main-content.visible {
            visibility: visible;
            opacity: 1;
        }
        
        /* --- NAVIGATION BAR --- */
        .main-nav {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: var(--nav-height);
            z-index: 1000;
            background: rgba(10, 10, 10, 0.8);
            backdrop-filter: blur(15px);
            border-bottom: 1px solid var(--border-color);
            display: flex;
            align-items: center;
        }
        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        .nav-logo {
            font-size: 2rem;
            font-weight: 900;
            color: #fff;
        }
        .nav-links {
            display: flex;
            align-items: center;
            gap: 30px;
            list-style: none;
        }
        .nav-links a {
            color: #a0a0a0;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        .nav-links a:hover {
            color: #fff;
        }
        .nav-button {
            background: var(--primary-blue);
            color: #fff;
            padding: 8px 20px;
            border-radius: 20px;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        .nav-button:hover {
            color: #fff;
            box-shadow: 0 0 15px var(--glow-color);
            transform: translateY(-2px);
        }

        /* --- ALL PREVIOUS STYLES --- */
        .background-animation {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: linear-gradient(45deg, var(--dark-bg) 0%, #001f3f 50%, var(--dark-bg) 100%);
            background-size: 400% 400%;
            animation: gradient-flow 15s ease-in-out infinite;
            z-index: -1;
        }

        @keyframes gradient-flow {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .section {
            padding: 100px 0;
            position: relative;
        }
        
        .section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                linear-gradient(rgba(255, 255, 255, 0.03) 1px, transparent 1px),
                linear-gradient(90deg, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
            background-size: 50px 50px;
            z-index: -1;
            opacity: 0.5;
        }


        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            padding-top: var(--nav-height); /* Added padding for fixed nav */
        }

        .hero h1 {
            font-size: clamp(3rem, 8vw, 6rem);
            font-weight: 900;
            line-height: 1.1;
            letter-spacing: -2px;
            background: linear-gradient(45deg, #fff, var(--primary-blue));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: clamp(1rem, 3vw, 1.5rem);
            color: #a0a0a0;
            max-width: 800px;
            margin: 0 auto;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 100px;
            align-items: center;
        }

        @media (min-width: 768px) {
            .feature-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            .feature-grid.reversed .content {
                order: 2;
            }
        }

        .content h2 {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary-blue);
            margin-bottom: 20px;
        }

        .content p, .content ul {
            font-size: 1.1rem;
            line-height: 1.7;
            color: #b0b0b0;
            margin-bottom: 15px;
        }
        
        .content ul {
            list-style: none;
            padding-left: 0;
        }
        
        .content li {
            padding-left: 25px;
            position: relative;
        }

        .content li::before {
            content: '✓';
            color: var(--primary-blue);
            position: absolute;
            left: 0;
        }

        .video-container {
            position: relative;
            width: 100%;
            aspect-ratio: 9 / 16;
            background-color: #000;
            border-radius: 12px;
            border: 2px solid rgba(0, 170, 255, 0.3);
            box-shadow: 0 0 30px var(--glow-color);
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden; 
        }
        
        .video-container iframe {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 100%;
            height: 100%;
            border: none;
            transform: translate(-50%, -50%) scale(1.15); 
        }

        .video-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .roadmap-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 60px;
        }

        .roadmap-card {
            background-color: var(--dark-card);
            padding: 30px;
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .roadmap-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
        }

        .roadmap-card .icon {
            font-size: 2.5rem;
            color: var(--primary-blue);
            margin-bottom: 15px;
        }

        .roadmap-card h3 {
            font-size: 1.5rem;
            color: #fff;
            margin-bottom: 10px;
        }

        .roadmap-card p {
            color: #b0b0b0;
            line-height: 1.6;
        }
        
        .reveal {
            opacity: 0;
            transform: translateY(50px);
            transition: opacity 0.8s ease, transform 0.8s ease;
        }
        .reveal.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .cta-button {
            display: inline-block;
            margin-top: 40px;
            background: linear-gradient(45deg, var(--primary-blue), #0077b6);
            color: #fff;
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1rem;
            box-shadow: 0 5px 20px rgba(0, 170, 255, 0.4);
            transition: all 0.3s ease;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(0, 170, 255, 0.6);
        }

        footer h2 {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary-blue);
            margin-bottom: 20px;
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
        }
    </style>
</head>
<body>

    <div id="password-gate">
        <div class="gate-container">
            <h1>Investor Access Only</h1>
            <p>This deck outlines the future of culture and commerce. Got the code? You’re in.</p>
            <form id="gate-form">
                <input type="password" id="password-input" placeholder="Enter Password">
                <button type="submit" class="gate-button">Unlock</button>
            </form>
            <p id="error-message">Incorrect Password. Please try again.</p>
        </div>
    </div>

    <div id="main-content">
        <nav class="main-nav">
            <div class="nav-container">
                <div class="nav-logo">UNI</div>
                <ul class="nav-links">
                    <li><a href="http://www.socialdna.xyz" target="_blank">B2B Demo</a></li>
                    <li><a href="#">Team</a></li>
                    <li><a href="https://calendly.com/isaiah-gouni/30min" target="_blank" class="nav-button">Schedule a Call</a></li>
                </ul>
            </div>
        </nav>

        <div class="background-animation"></div>

        <header class="hero section">
            <div class="container reveal">
                <h1>The Real-World Operating System.</h1>
                <p>We're building the intelligent infrastructure that connects every physical experience, venue, and social interaction into one unified platform. This is not another app. This is the new reality.</p>
                <a href="https://calendly.com/isaiah-gouni/30min" target="_blank" class="cta-button">Schedule a Call with the CEO</a>
            </div>
        </header>

        <main>
            <section id="interactive-map" class="section">
                <div class="container feature-grid">
                    <div class="content reveal">
                        <h2>The City At Your Fingertips</h2>
                        <p>Every “blip” on the map is a live gateway to the city's pulse. Each point is fully interactable, opening into a dynamic profile card with everything you need to know.</p>
                        <ul>
                            <li>Real-time hours, tags, and venue info.</li>
                            <li>Instant RSVP and booking capabilities.</li>
                            <li>V2 will feature dynamic images from Foursquare and partner venues.</li>
                        </ul>
                    </div>
                    
                    <div class="video-container reveal">
                        <iframe src="https://streamable.com/e/5xvxab?autoplay=1&muted=1&loop=1&controls=0" allow="autoplay" allowfullscreen></iframe>
                    </div>

                </div>
            </section>

            <section id="experience-engine" class="section">
                <div class="container feature-grid reversed">
                    <div class="content reveal">
                        <h2>The Experience Engine</h2>
                        <p>Powered by OpenAI, our engine lets you command the city with natural language. We parse your location, intent, category, and context to deliver hyper-relevant results in real time.</p>
                        <p><strong>Coming Soon:</strong> Conversational memory, keyword highlighting, AI-crafted itinerary bundles, and smarter results trained on the Foursquare API.</p>
                    </div>

                    <div class="video-container reveal">
                        <iframe src="https://streamable.com/e/syolsv?autoplay=1&muted=1&loop=1&controls=0" allow="autoplay" allowfullscreen></iframe>
                    </div>
                </div>
            </section>

            <section id="social-layer" class="section">
                <div class="container feature-grid">
                    <div class="content reveal">
                        <h2>The Social Layer</h2>
                        <p><strong>Smart Guest Lists:</strong> Connect before you arrive. We surface the most compatible attendees at any event based on shared interests and Social DNA. Find your vibe, not just a crowd.</p>
                        <p><strong>UNI Friends:</strong> A hybrid of Tinder, Find My Friends, and GroupMe. Discover new connections, manage real-life friendships on a live dashboard, and coordinate plans seamlessly.</p>
                         <p><strong>My Plans:</strong> Your personal command center for the real world. View saved places, see your RSVPs, and create your own events with flyers, tags, and guest lists.</p>
                    </div>

                    <div class="video-container reveal">
                        <iframe src="https://streamable.com/e/xwp5iv?autoplay=1&muted=1&loop=1&controls=0" allow="autoplay" allowfullscreen></iframe>
                    </div>
                </div>
            </section>

            <section id="roadmap" class="section">
                <div class="container">
                    <div class="content reveal" style="text-align: center; max-width: 800px; margin: 0 auto;">
                        <h2>What’s Coming Sooner Than Later</h2>
                        <p>The foundation is built. Now we scale reality.</p>
                    </div>

                    <div class="roadmap-grid">
                        <div class="roadmap-card reveal">
                            <div class="icon">👤</div>
                            <h3>Face Authentication</h3>
                            <p>A trust layer to eliminate bots and fake profiles. Light face verification ensures guest list authenticity and platform integrity for rewards and check-ins.</p>
                        </div>
                        <div class="roadmap-card reveal">
                            <div class="icon">🔥</div>
                            <h3>Matchmaking for Places</h3>
                            <p>Tinder for Outside. Swipe on events, venues, and the profiles of others swiping on the same experiences. It's not dating—it's finding your crowd.</p>
                        </div>
                        <div class="roadmap-card reveal">
                            <div class="icon">🛰️</div>
                            <h3>Airmatch</h3>
                            <p>AirDrop for people. Instantly discover and connect with compatible users in the same physical space using profile barcodes or automatic detection.</p>
                        </div>
                        <div class="roadmap-card reveal">
                            <div class="icon">🤖</div>
                            <h3>AI Travel Planning</h3>
                            <p>Your real-life itinerary engine. Ask UNI to plan a bar crawl, a date night, or a solo weekend, and get a full plan built in seconds.</p>
                        </div>
                        <div class="roadmap-card reveal">
                            <div class="icon">📸</div>
                            <h3>UNI Stories</h3>
                            <p>A social proof and memory system powered by real movement. Every check-in becomes a data trigger and a visual record of where the night went.</p>
                        </div>
                        <div class="roadmap-card reveal">
                            <div class="icon">📂</div>
                            <h3>Curated Folder Marketplace</h3>
                            <p>A monetizable system for users and influencers to create, share, and sell custom "event playlists" and city guides, driving community-led curation.</p>
                        </div>
                    </div>
                </div>
            </section>

        </main>

        <footer class="section" style="text-align: center;">
            <div class="container reveal">
                <h2>Ready to Build the Future?</h2>
                <p style="max-width: 600px; margin: 20px auto 40px; color: #a0a0a0;">Let's connect and discuss how UNI will become the definitive operating system for the real world.</p>
                <a href="https://calendly.com/isaiah-gouni/30min" target="_blank" class="cta-button">Schedule a 30-Minute Call</a>
            </div>
        </footer>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const passwordGate = document.getElementById('password-gate');
            const gateForm = document.getElementById('gate-form');
            const passwordInput = document.getElementById('password-input');
            const errorMessage = document.getElementById('error-message');
            const mainContent = document.getElementById('main-content');
            const gateContainer = document.querySelector('.gate-container');

            if (sessionStorage.getItem('isVerified') === 'true') {
                passwordGate.style.display = 'none';
                mainContent.classList.add('visible');
                initializeAnimations();
            }

            gateForm.addEventListener('submit', (e) => {
                e.preventDefault();
                const input = passwordInput.value;

                if (input === 'UNIcorn') {
                    sessionStorage.setItem('isVerified', 'true');
                    passwordGate.classList.add('hidden');
                    setTimeout(() => {
                        passwordGate.style.display = 'none';
                        mainContent.classList.add('visible');
                        initializeAnimations();
                    }, 500);
                } else {
                    errorMessage.style.visibility = 'visible';
                    passwordInput.value = '';
                    gateContainer.classList.add('shake');
                    setTimeout(() => {
                        gateContainer.classList.remove('shake');
                    }, 500);
                }
            });

            function initializeAnimations() {
                const revealElements = document.querySelectorAll('.reveal');
                if (revealElements.length > 0) {
                    const observer = new IntersectionObserver((entries) => {
                        entries.forEach(entry => {
                            if (entry.isIntersecting) {
                                entry.target.classList.add('visible');
                            }
                        });
                    }, {
                        threshold: 0.1
                    });
                    revealElements.forEach(el => {
                        observer.observe(el);
                    });
                }
            }
        });
    </script>
</body>
</html>
