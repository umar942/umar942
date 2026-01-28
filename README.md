<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200">
  <!-- Background with improved gradient -->
  <rect width="800" height="200"  fill="url(#grad)" />
  
  <!-- Gradient definition -->
  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f2027;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#203a43;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#2c5364;stop-opacity:1" />
    </linearGradient>
    
    <!-- Animation styles -->
    <style>
      @keyframes blink {
        0%, 100% { opacity: 1; }
        50% { opacity: 0; }
      }
      
      .cursor {
        animation: blink 1s infinite;
      }
      
      @keyframes float {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-15px); }
      }
      
      .floating {
        animation: float 4s ease-in-out infinite;
      }

      
      /* Improved typing animation */
      @keyframes typing1 { 0% { opacity: 0; } 4% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing2 { 0% { opacity: 0; } 4% { opacity: 0; } 8% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing3 { 0% { opacity: 0; } 8% { opacity: 0; } 12% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing4 { 0% { opacity: 0; } 12% { opacity: 0; } 16% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing5 { 0% { opacity: 0; } 16% { opacity: 0; } 20% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing6 { 0% { opacity: 0; } 20% { opacity: 0; } 24% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing7 { 0% { opacity: 0; } 24% { opacity: 0; } 28% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing8 { 0% { opacity: 0; } 28% { opacity: 0; } 32% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing9 { 0% { opacity: 0; } 32% { opacity: 0; } 36% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing10 { 0% { opacity: 0; } 36% { opacity: 0; } 40% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing11 { 0% { opacity: 0; } 40% { opacity: 0; } 44% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing12 { 0% { opacity: 0; } 44% { opacity: 0; } 48% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing13 { 0% { opacity: 0; } 48% { opacity: 0; } 52% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing14 { 0% { opacity: 0; } 52% { opacity: 0; } 56% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing15 { 0% { opacity: 0; } 56% { opacity: 0; } 60% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing16 { 0% { opacity: 0; } 60% { opacity: 0; } 64% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing17 { 0% { opacity: 0; } 64% { opacity: 0; } 68% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing18 { 0% { opacity: 0; } 68% { opacity: 0; } 72% { opacity: 1; } 100% { opacity: 1; } }
      @keyframes typing19 { 0% { opacity: 0; } 72% { opacity: 0; } 76% { opacity: 1; } 100% { opacity: 1; } }
      
      .typing-char-1 { animation: typing1 4s linear forwards; opacity: 0; }
      .typing-char-2 { animation: typing2 4s linear forwards; opacity: 0; }
      .typing-char-3 { animation: typing3 4s linear forwards; opacity: 0; }
      .typing-char-4 { animation: typing4 4s linear forwards; opacity: 0; }
      .typing-char-5 { animation: typing5 4s linear forwards; opacity: 0; }
      .typing-char-6 { animation: typing6 4s linear forwards; opacity: 0; }
      .typing-char-7 { animation: typing7 4s linear forwards; opacity: 0; }
      .typing-char-8 { animation: typing8 4s linear forwards; opacity: 0; }
      .typing-char-9 { animation: typing9 4s linear forwards; opacity: 0; }
      .typing-char-10 { animation: typing10 4s linear forwards; opacity: 0; }
      .typing-char-11 { animation: typing11 4s linear forwards; opacity: 0; }
      .typing-char-12 { animation: typing12 4s linear forwards; opacity: 0; }
      .typing-char-13 { animation: typing13 4s linear forwards; opacity: 0; }
      .typing-char-14 { animation: typing14 4s linear forwards; opacity: 0; }
      .typing-char-15 { animation: typing15 4s linear forwards; opacity: 0; }
      .typing-char-16 { animation: typing16 4s linear forwards; opacity: 0; }
      .typing-char-17 { animation: typing17 4s linear forwards; opacity: 0; }
      .typing-char-18 { animation: typing18 4s linear forwards; opacity: 0; }
      .typing-char-19 { animation: typing19 4s linear forwards; opacity: 0; }

      @keyframes cursorAnimation {
        0%, 75% { opacity: 0; }
        76% { opacity: 1; }
        77%, 100% { animation-timing-function: steps(1); }
      }
      
      .cursor-final {
        animation: blink 1s infinite;
        animation-delay: 3s;
        opacity: 0;
      }
      
      @keyframes slideIn {
        0% { transform: translateX(-50px); opacity: 0; }
        100% { transform: translateX(0); opacity: 1; }
      }
      
      .tech-stack text {
        animation: slideIn 0.5s ease-out forwards;
        opacity: 0;
      }
      
      .tech-stack text:nth-child(1) { animation-delay: 0.1s; }
      .tech-stack text:nth-child(2) { animation-delay: 0.3s; }
      .tech-stack text:nth-child(3) { animation-delay: 0.5s; }
      .tech-stack text:nth-child(4) { animation-delay: 0.7s; }
      .tech-stack text:nth-child(5) { animation-delay: 0.9s; }
      .tech-stack text:nth-child(6) { animation-delay: 1.1s; }
      
      @keyframes highlight {
        0%, 100% { filter: drop-shadow(0 0 2px rgba(255,255,255,0.3)); }
        50% { filter: drop-shadow(0 0 10px rgba(255,255,255,0.7)); }
      }
      
      .highlight {
        animation: highlight 3s ease-in-out infinite;
      }
    </style>
  </defs>
  
  <!-- Main title with highlight effect -->
  <g class="highlight">
    <text x="400" y="70" font-family="Arial, sans-serif" font-size="42" font-weight="bold" fill="white" text-anchor="middle">Umali Ali</text>
  </g>
  
  <!-- Subtitle with character-by-character typing animation -->
  <g font-family="Arial, sans-serif" font-size="28" font-weight="bold" fill="#61DAFB" text-anchor="middle">
    <!-- Each character with its own animation -->
    <text x="265" y="110" class="typing-char-1">F</text>
    <text x="281" y="110" class="typing-char-2">u</text>
    <text x="295" y="110" class="typing-char-3">l</text>
    <text x="305" y="110" class="typing-char-4">l</text>
    <text x="320" y="110" class="typing-char-5"> </text>
    <text x="335" y="110" class="typing-char-6">S</text>
    <text x="350" y="110" class="typing-char-7">t</text>
    <text x="364" y="110" class="typing-char-8">a</text>
    <text x="379" y="110" class="typing-char-9">c</text>
    <text x="395" y="110" class="typing-char-10">k</text>
    <text x="405" y="110" class="typing-char-11"> </text>
    <text x="420" y="110" class="typing-char-12">D</text>
    <text x="440" y="110" class="typing-char-13">e</text>
    <text x="457" y="110" class="typing-char-14">v</text>
    <text x="473" y="110" class="typing-char-15">e</text>
    <text x="486" y="110" class="typing-char-16">l</text>
    <text x="499" y="110" class="typing-char-17">o</text>
    <text x="517" y="110" class="typing-char-18">p</text>
    <text x="533" y="110" class="typing-char-19">e</text>
    <text x="547" y="110" class="typing-char-19">r</text>
  </g>
  
  <!-- Blinking cursor that appears after typing -->
  <text x="555" y="110" font-family="monospace" font-size="28" fill="#61DAFB" class="cursor-final">|</text>
  
  <!-- Description -->
  <text x="400" y="145" font-family="monospace" font-size="18" fill="#ccc" text-anchor="middle">Building elegant solutions from front to back</text>
  
  <!-- Tech stack with improved alignment and animation -->
  <g class="tech-stack">
    <text x="150" y="175" font-family="monospace" font-size="16" fill="#EEEE" text-anchor="middle">Next</text>
    <text x="230" y="175" font-family="monospace" font-size="16" fill="#61DAFB" text-anchor="middle">Tailwind</text>
    <text x="320" y="175" font-family="monospace" font-size="16" fill="#F7DF1E" text-anchor="middle">JavaScript</text>
    <text x="420" y="175" font-family="monospace" font-size="16" fill="#61DAFB" text-anchor="middle">React</text>
    <text x="510" y="175" font-family="monospace" font-size="16" fill="#3C873A" text-anchor="middle">Node.js</text>
    <text x="610" y="175" font-family="monospace" font-size="16" fill="#4479A1" text-anchor="middle">MongoDB</text>
  </g>
  
  <!-- Decorative connecting lines -->
  <g stroke-dasharray="5,5" stroke-width="1.5" stroke-opacity="0.6">
    <path d="M150,120 C250,80 350,70 400,70" stroke="#61DAFB" fill="none" />
    <path d="M650,120 C550,80 450,70 400,70" stroke="#F06529" fill="none" />
  </g>
  
  <!-- Small code particles -->
  <g class="floating" style="animation-delay: -2s">
    <circle cx="200" cy="50" r="4" fill="#F7DF1E" />
    <circle cx="220" cy="70" r="3" fill="#264DE4" />
    <circle cx="180" cy="40" r="2" fill="#E44D26" />
  </g>
  <g class="floating" style="animation-delay: -1s">
    <circle cx="600" cy="50" r="4" fill="#3C873A" />
    <circle cx="580" cy="70" r="3" fill="#61DAFB" />
    <circle cx="620" cy="40" r="2" fill="#4479A1" />
  </g>
</svg>


# 💫 About Me:
Hi, I'm Umar Ali <br><br>I'm a passionate Web & Mobile Developer who loves crafting modern, responsive, and interactive digital experiences. I specialize in frontend


## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/www.linkedin.com/in/umar-ali-6501a2353) 

# 💻 Tech Stack:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=umar942&theme=shadow_blue&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=umar942&theme=shadow_blue&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=umar942&theme=shadow_blue&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=umar942&theme=radical&no-frame=false&no-bg=false&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)


---
[![](https://visitcount.itsvg.in/api?id=umar942&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->


