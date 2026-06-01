# Hi, I'm Ronan Antoque 👋
### <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=38B2AC&width=435&lines=BSIT+Student;Aspiring+Frontend+Engineer;Full-Stack+Explorer" alt="Typing SVG" />

<!-- NATIVE INLINE SVG ANIMATION SYSTEM -->
<svg viewBox="0 0 800 200" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; border-radius: 8px; border: 1px solid #21262d;">
  <defs>
    <!-- Cyan Glow Filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>
    
    <!-- Linear Gradients for Data Nodes -->
    <linearGradient id="cyanGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00f2fe" />
      <stop offset="100%" stop-color="#4facfe" />
    </linearGradient>

    <!-- Keyframe Animations via SVG Style Block -->
    <style>
      @keyframes pulse {
        0% { opacity: 0.3; transform: scale(0.98); }
        50% { opacity: 0.9; filter: drop-shadow(0 0 8px #38B2AC); transform: scale(1.02); }
        100% { opacity: 0.3; transform: scale(0.98); }
      }
      @keyframes dash {
        to { stroke-dashoffset: -40; }
      }
      @keyframes float {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-5px); }
        100% { transform: translateY(0px); }
      }
      .bg-grid { stroke: #161b22; stroke-width: 1; }
      .circuit-line { stroke: #1f2937; stroke-width: 2; fill: none; }
      .active-stream { stroke: url(#cyanGrad); stroke-width: 2; stroke-dasharray: 8, 12; animation: dash 2s linear infinite; fill: none; }
      .core-logo { transform-origin: 400px 100px; animation: pulse 4s ease-in-out infinite; }
      .floating-node { animation: float 3s ease-in-out infinite; }
      .tech-text { font-family: 'Fira Code', monospace; font-size: 11px; fill: #8b949e; }
    </style>
  </defs>

  <!-- Background Tech Grid Pattern -->
  <path class="bg-grid" d="M0 25 H800 M0 50 H800 M0 75 H800 M0 100 H800 M0 125 H800 M0 150 H800 M0 175 H800" />
  <path class="bg-grid" d="M50 0 V200 M100 0 V200 M150 0 V200 M200 0 V200 M250 0 V200 M300 0 V200 M350 0 V200 M400 0 V200 M450 0 V200 M500 0 V200 M550 0 V200 M600 0 V200 M650 0 V200 M700 0 V200 M750 0 V200" />

  <!-- Animated Circuit Line Traces -->
  <path class="circuit-line" d="M 150 50 H 300 L 350 100 H 450 L 500 150 H 650" />
  <path class="circuit-line" d="M 150 150 H 320 L 370 100 H 480 L 520 50 H 650" />
  
  <path class="active-stream" d="M 150 50 H 300 L 350 100 H 450 L 500 150 H 650" />
  <path class="active-stream" d="M 150 150 H 320 L 370 100 H 480 L 520 50 H 650" />

  <!-- Outer Tech HUD Rings -->
  <circle cx="400" cy="100" r="45" fill="none" stroke="#1f2937" stroke-width="1" />
  <circle cx="400" cy="100" r="52" fill="none" stroke="#38B2AC" stroke-width="1" stroke-dasharray="10, 25" style="transform-origin: 400px 100px; animation: dash 8s linear infinite;" />

  <!-- Central RS Neon Shield Node -->
  <g class="core-logo">
    <circle cx="400" cy="100" r="38" fill="#0d1117" stroke="#38B2AC" stroke-width="2" filter="url(#glow)" />
    <text x="400" y="108" font-family="'Segoe UI', sans-serif" font-weight="900" font-size="24" fill="#00f2fe" text-anchor="middle" letter-spacing="1">RS</text>
  </g>

  <!-- Left Side Node: Status Window -->
  <g class="floating-node" style="animation-delay: 0s;">
    <rect x="50" y="65" width="160" height="70" rx="6" fill="#161b22" stroke="#30363d" stroke-width="1" />
    <circle cx="65" cy="77" r="3" fill="#ff5f56" />
    <circle cx="75" cy="77" r="3" fill="#ffbd2e" />
    <circle cx="85" cy="77" r="3" fill="#27c93f" />
    <text x="62" y="105" class="tech-text" fill="#38B2AC" font-weight="bold">> Learning:</text>
    <text x="62" y="122" class="tech-text" fill="#ffffff">React &amp; .NET</text>
  </g>

  <!-- Right Side Node: Architecture Context -->
  <g class="floating-node" style="animation-delay: 1.5s;">
    <rect x="590" y="65" width="160" height="70" rx="6" fill="#161b22" stroke="#30363d" stroke-width="1" />
    <circle cx="605" cy="77" r="3" fill="#ff5f56" />
    <circle cx="615" cy="77" r="3" fill="#ffbd2e" />
    <circle cx="625" cy="77" r="3" fill="#27c93f" />
    <text x="602" y="105" class="tech-text" fill="#38B2AC" font-weight="bold">> Engineering</text>
    <text x="602" y="122" class="tech-text" fill="#ffffff">Full-Stack Hub</text>
  </g>
</svg>

<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

---

## 🚀 About Me
- 🎓 **Education:** 3rd Year BSIT Student at the University of Cebu Main Campus.
- 💻 **Focus:** Crafting clean, responsive user interfaces and building optimized web systems.
- 📚 **Currently Leveling Up:** Actively expanding my frontend ecosystem with **React** and diving into backend robust architecture with **.NET development**.
- ⚙️ **Tech Mindset:** Blending solid full-stack backend logic with pixel-perfect frontend layouts.

---

## 🛠️ Featured Projects & Systems

### 🖥️ Sit-in Monitoring System
> A specialized dashboard management tool engineered with **PHP** and **Tailwind CSS** to streamline and log student hours seamlessly.
*🔧 Status: In active development / core features implementation.*

### 🔒 Secure Vault
> A web application UI focused on secure data handling, built with a modern frontend architecture to keep information encrypted and clean.

---

## 📊 GitHub Profile Metrics

<p align="left">
  <img src="https://github-profile-trophy.vercel.app/?username=RonanStack24&theme=tokyonight&no-bg=true&margin-w=15" alt="Ronan's Trophies" />
</p>

---

## ⚡ Beyond the Code
* 🌲 **Mindset & Focus:** When I am AFK, I choose to decouple from the screens. You can find me spending time out in nature or reading books to clear my mind, keep my perspectives grounded, and maintain a chill, focused approach to problem-solving.
