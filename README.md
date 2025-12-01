<style>
    /* 1. Global Setup (Dark Mode Foundation) */
    .cyber-profile-container {
        font-family: 'Consolas', 'Courier New', monospace; /* Monospaced for a tech feel */
        background-color: #010409; /* Deep Black background */
        color: #00ff7f; /* Neon Green default text */
        padding: 30px 0;
        overflow: hidden; /* Important for animations */
        text-align: center;
    }

    /* 2. Keyframe Animations */
    
    /* Neon Pulse for glowing elements */
    @keyframes neonPulse {
        0% { box-shadow: 0 0 5px #00ff7f, 0 0 10px #00ff7f; }
        50% { box-shadow: 0 0 10px #00e5e5, 0 0 20px #00e5e5; }
        100% { box-shadow: 0 0 5px #00ff7f, 0 0 10px #00ff7f; }
    }

    /* Scanner Effect for text */
    @keyframes textScanner {
        0% { opacity: 0.5; text-shadow: 0 0 1px #ff00c3; }
        70% { opacity: 1; text-shadow: 0 0 5px #00ff7f; }
        100% { opacity: 0.5; text-shadow: 0 0 1px #ff00c3; }
    }

    /* Holographic Glitch for cards on hover */
    @keyframes holographicGlitch {
        0%, 100% { transform: translate(0, 0); }
        20% { transform: translate(-2px, 2px); }
        40% { transform: translate(2px, -2px); }
        60% { transform: translate(-1px, 1px); }
        80% { transform: translate(1px, -1px); }
    }

    /* 3. Hero Section Styling */
    .hero-holographic {
        background: linear-gradient(135deg, #0c1421 0%, #171d2b 100%);
        border: 2px solid #ff00c3; /* Magenta border */
        border-radius: 12px;
        padding: 50px 20px;
        margin-bottom: 40px;
        position: relative;
        animation: neonPulse 3s infinite alternate; /* Apply neon pulse */
    }

    .hero-title {
        color: #00e5e5; /* Cyan for main title */
        font-size: 3em;
        font-weight: 700;
        margin-bottom: 10px;
        text-shadow: 0 0 10px #00e5e5;
        animation: textScanner 2s infinite ease-in-out; /* Apply scanner animation */
    }

    .hero-subtitle {
        color: #ff00c3; /* Magenta subtitle */
        font-size: 1.3em;
        font-style: italic;
    }

    /* 4. Section Card Styling (The core container) */
    .cyber-card {
        background-color: #0c1421; /* Dark card background */
        border-radius: 8px;
        padding: 25px;
        margin-bottom: 30px;
        box-shadow: 0 0 15px rgba(0, 255, 127, 0.2); /* Soft green glow */
        transition: all 0.4s ease-in-out;
        text-align: left;
        position: relative;
    }

    .cyber-card:hover {
        border-left: 5px solid #ff00c3; /* Magenta indicator on hover */
        box-shadow: 0 0 25px rgba(0, 229, 229, 0.4); /* Stronger cyan glow */
        animation: holographicGlitch 0.5s 1; /* Quick glitch on hover */
    }

    /* 5. Heading Styling */
    .cyber-heading {
        color: #00ff7f; /* Neon Green */
        font-size: 1.8em;
        padding-bottom: 8px;
        margin-bottom: 20px;
        border-bottom: 2px dashed #ff00c3;
        font-weight: 600;
    }

    /* 6. Technology Badges - Advanced Glow */
    .tech-grid {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
    }

    .tech-badge-colorful {
        display: inline-block;
        padding: 8px 15px;
        border-radius: 5px;
        font-size: 0.9em;
        font-weight: bold;
        transition: all 0.3s ease;
        text-transform: uppercase;
        letter-spacing: 1px;
        background: #171d2b;
        border: 1px solid #00e5e5;
        color: #00e5e5;
    }

    .tech-badge-colorful:hover {
        background: #ff00c3; /* Magenta background on hover */
        color: #010409;
        box-shadow: 0 0 10px #ff00c3;
        transform: scale(1.05);
    }
    
    /* 7. Stats Layout - Grid for modern look */
    .stats-layout-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
        justify-content: center;
        text-align: center;
    }

    .stats-layout-grid img {
        width: 100%;
        height: auto;
        border-radius: 8px;
        /* Custom card background for stats cards (if applicable) */
        background-color: #0c1421; 
        padding: 10px; 
    }

    /* 8. Glitch Effect on Text (Used sparingly) */
    .glitch-text {
        font-weight: 700;
        color: #00ff7f;
        text-shadow: 1px 1px #ff00c3, -1px -1px #00e5e5;
        transition: text-shadow 0.3s ease;
    }

</style>



<div class="cyber-profile-container">

  <div class="hero-holographic">
        <h1 class="hero-title">INITIATING PROFILE SEQUENCE...</h1>
        <p class="hero-subtitle">-- Geo Cherian Mathew -- | System: ONLINE | Status: Coding.</p>
    </div>

   <div class="cyber-card">
        <h2 class="cyber-heading">📡 Developer Log // STATUS: ACTIVE</h2>
        <p style="line-height: 1.6; color: #c9d1d9;">
            <span class="glitch-text">ACCESS GRANTED.</span> I am a CSE student driven by the desire to merge design intuition with engineering precision.
            <br>
            My current objective involves specializing in AI/ML, Web Development,Computer Vision and contributing to open-source projects.
            <br>
            <br>
            **&gt; Contact Signal:** [gingercatmonster19@gmail.com]
            <br>
            **&gt; Portfolio Link:** <a href="https://geo-cherian-mathew-2k28.github.io/geo-portfolio/" style="color: #ff00c3; text-decoration: none;">[Your Portfolio URL]</a>
        </p>
    </div>

   <div class="cyber-card">
        <h2 class="cyber-heading">⚙️ Technology Matrix // CORE STACK</h2>
        <div class="tech-grid">
            <span class="tech-badge-colorful">React.js</span>
            <span class="tech-badge-colorful">Node.js</span>
            <span class="tech-badge-colorful">TypeScript</span>
            <span class="tech-badge-colorful">MongoDB</span>
            <span class="tech-badge-colorful">C++</span>
            <span class="tech-badge-colorful">Docker</span>
            <span class="tech-badge-colorful">AWS</span>
            <span class="tech-badge-colorful">Python</span>
        </div>
    </div>
    
  <div class="cyber-card">
        <h2 class="cyber-heading">📊 Performance Monitor // GITHUB STATS</h2>
        <div class="stats-layout-grid">
            <img src="https://github-readme-stats.vercel.app/api?username=[ritik307]&show_icons=true&theme=vue-dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
            
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[ritik307]&layout=compact&theme=vue-dark&hide_border=true" alt="Top Languages" />
        </div>
    </div>
    
   <div class="cyber-card" style="text-align: center;">
         <h2 class="cyber-heading">🔥 System Activity // STREAK DISPLAY</h2>
         <img src="https://github-readme-streak-stats.herokuapp.com/?user=[ritik307]&theme=dark&hide_border=true" alt="GitHub Streak" style="max-width: 600px;"/>
         <p style="margin-top: 15px; color: #00ff7f;">**Keep the streak alive. Keep the system running.**</p>
    </div>

</div>
