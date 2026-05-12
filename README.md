<svg width="100%" viewBox="0 0 900 320" xmlns="http://www.w3.org/2000/svg" role="img">
  <title>Lucas Manassés - Full Stack Developer</title>
  <desc>Banner animado com desenvolvedor digitando e apresentação profissional</desc>
 
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1b2e"/>
      <stop offset="100%" style="stop-color:#0a0e1a"/>
    </linearGradient>
    <linearGradient id="monitorGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a2744"/>
      <stop offset="100%" style="stop-color:#0d1830"/>
    </linearGradient>
    <linearGradient id="screenGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#111827"/>
    </linearGradient>
    <linearGradient id="deskGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#2d2016"/>
      <stop offset="100%" style="stop-color:#1a110a"/>
    </linearGradient>
    <linearGradient id="chairGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#3d2b1a"/>
      <stop offset="100%" style="stop-color:#1a110a"/>
    </linearGradient>
    <linearGradient id="glowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#00d4ff;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#00d4ff;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="shirtGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#2d4a2d"/>
      <stop offset="100%" style="stop-color:#1a2e1a"/>
    </linearGradient>
    <linearGradient id="skinGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#c8956c"/>
      <stop offset="100%" style="stop-color:#a8734a"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <clipPath id="screenClip">
      <rect x="175" y="52" width="220" height="155" rx="4"/>
    </clipPath>
  </defs>
 
  <!-- Background -->
  <rect width="900" height="320" fill="url(#bgGrad)"/>
 
  <!-- Background ambient glow from monitor -->
  <ellipse cx="310" cy="180" rx="180" ry="120" fill="#00d4ff" opacity="0.03"/>
  <ellipse cx="310" cy="130" rx="140" ry="80" fill="#3b82f6" opacity="0.04"/>
 
  <!-- ===================== ROOM ELEMENTS ===================== -->
 
  <!-- Back wall panels suggestion -->
  <rect x="60" y="20" width="520" height="260" fill="none" stroke="#1a2030" stroke-width="0.5" rx="2"/>
 
  <!-- Plant pot (left) -->
  <ellipse cx="90" cy="220" rx="22" ry="8" fill="#2d1f0f"/>
  <rect x="74" y="190" width="32" height="30" fill="#3d2a14" rx="3"/>
  <!-- Plant leaves -->
  <ellipse cx="90" cy="185" rx="15" ry="8" fill="#1a3d1a" transform="rotate(-20 90 185)"/>
  <ellipse cx="95" cy="178" rx="14" ry="7" fill="#1f4a1f" transform="rotate(10 95 178)"/>
  <ellipse cx="82" cy="180" rx="12" ry="6" fill="#1a3d1a" transform="rotate(-35 82 180)"/>
  <ellipse cx="98" cy="170" rx="10" ry="5" fill="#16331a" transform="rotate(25 98 170)"/>
 
  <!-- ===================== DESK ===================== -->
  <rect x="100" y="218" width="400" height="14" fill="url(#deskGrad)" rx="2"/>
  <!-- Desk front -->
  <rect x="103" y="228" width="394" height="6" fill="#120c06" rx="1"/>
  <!-- Desk glow strip (cyan ambient light) -->
  <rect x="108" y="220" width="388" height="2" fill="url(#glowGrad)" opacity="0.6"/>
 
  <!-- ===================== CHAIR ===================== -->
  <!-- Chair back -->
  <rect x="320" y="145" width="55" height="80" fill="url(#chairGrad)" rx="6"/>
  <rect x="326" y="151" width="43" height="68" fill="#2a1d0e" rx="4"/>
  <!-- Chair seat -->
  <rect x="310" y="210" width="75" height="16" fill="#3d2b1a" rx="4"/>
  <!-- Chair legs -->
  <line x1="318" y1="226" x2="313" y2="280" stroke="#1a110a" stroke-width="5"/>
  <line x1="377" y1="226" x2="382" y2="280" stroke="#1a110a" stroke-width="5"/>
 
  <!-- ===================== MONITOR STAND ===================== -->
  <rect x="272" y="196" width="16" height="24" fill="#1a2540" rx="2"/>
  <rect x="255" y="216" width="50" height="6" fill="#1a2540" rx="3"/>
 
  <!-- ===================== MONITOR ===================== -->
  <!-- Monitor outer bezel -->
  <rect x="162" y="42" width="248" height="162" fill="url(#monitorGrad)" rx="10"/>
  <!-- Monitor inner bezel -->
  <rect x="168" y="47" width="236" height="152" fill="#0a0f1e" rx="8"/>
  <!-- Screen -->
  <rect x="175" y="52" width="220" height="142" fill="url(#screenGrad)" rx="4"/>
 
  <!-- Screen content - code editor look -->
  <rect x="175" y="52" width="220" height="142" fill="#0d1117" rx="4" clip-path="url(#screenClip)"/>
 
  <!-- Code editor top bar -->
  <rect x="175" y="52" width="220" height="18" fill="#161b22" rx="4"/>
  <rect x="175" y="62" width="220" height="8" fill="#161b22"/>
  <!-- Window dots -->
  <circle cx="187" cy="61" r="3.5" fill="#ff5f57"/>
  <circle cx="197" cy="61" r="3.5" fill="#febc2e"/>
  <circle cx="207" cy="61" r="3.5" fill="#28c840"/>
 
  <!-- Code lines on screen -->
  <rect x="183" y="80" width="60" height="4" fill="#00d4ff" rx="2" opacity="0.9"/>
  <rect x="183" y="90" width="100" height="4" fill="#7dd3fc" rx="2" opacity="0.7"/>
  <rect x="183" y="100" width="80" height="4" fill="#c084fc" rx="2" opacity="0.7"/>
  <rect x="183" y="110" width="120" height="4" fill="#4ade80" rx="2" opacity="0.7"/>
  <rect x="183" y="120" width="90" height="4" fill="#7dd3fc" rx="2" opacity="0.6"/>
  <rect x="183" y="130" width="70" height="4" fill="#fbbf24" rx="2" opacity="0.7"/>
  <rect x="183" y="140" width="110" height="4" fill="#4ade80" rx="2" opacity="0.6"/>
  <rect x="183" y="150" width="55" height="4" fill="#c084fc" rx="2" opacity="0.6"/>
 
  <!-- Typing cursor blink on screen -->
  <rect x="183" y="162" width="2" height="10" fill="#00d4ff" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
 
  <!-- Screen glow reflection -->
  <rect x="175" y="52" width="220" height="142" fill="none" stroke="#00d4ff" stroke-width="0.5" rx="4" opacity="0.3"/>
 
  <!-- Monitor ambient glow on desk -->
  <ellipse cx="285" cy="225" rx="80" ry="10" fill="#00d4ff" opacity="0.06"/>
 
  <!-- ===================== KEYBOARD ===================== -->
  <rect x="213" y="222" width="145" height="14" fill="#1a2540" rx="4"/>
  <rect x="216" y="224" width="139" height="10" fill="#0f1929" rx="3"/>
  <!-- Key rows suggestion -->
  <rect x="220" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="231" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="242" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="253" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="264" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="275" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="286" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="297" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="308" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="319" y="226" width="8" height="3" fill="#243052" rx="1"/>
  <rect x="222" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="231" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="240" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="249" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="258" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="267" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="276" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="285" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="294" y="231" width="6" height="3" fill="#243052" rx="1"/>
  <rect x="303" y="231" width="6" height="3" fill="#243052" rx="1"/>
 
  <!-- ===================== PERSON ===================== -->
 
  <!-- Body / shirt (seen from side/back) -->
  <path d="M330 155 Q340 145 355 142 Q370 140 380 148 L388 218 Q365 222 340 218 Z" fill="url(#shirtGrad)"/>
 
  <!-- Upper arm (left, extended toward keyboard) -->
  <path d="M335 165 Q310 178 275 222" stroke="url(#shirtGrad)" stroke-width="22" fill="none" stroke-linecap="round"/>
  <!-- Forearm / hand on keyboard -->
  <path d="M275 222 Q255 225 240 228" stroke="url(#skinGrad)" stroke-width="12" fill="none" stroke-linecap="round"/>
 
  <!-- Fingers typing (animated) -->
  <g>
    <circle cx="234" cy="229" r="5" fill="url(#skinGrad)">
      <animate attributeName="cy" values="229;227;229" dur="0.4s" repeatCount="indefinite" begin="0s"/>
    </circle>
    <circle cx="245" cy="228" r="5" fill="url(#skinGrad)">
      <animate attributeName="cy" values="228;226;228" dur="0.4s" repeatCount="indefinite" begin="0.1s"/>
    </circle>
    <circle cx="256" cy="228" r="5" fill="url(#skinGrad)">
      <animate attributeName="cy" values="228;226;228" dur="0.4s" repeatCount="indefinite" begin="0.2s"/>
    </circle>
    <circle cx="267" cy="228" r="5" fill="url(#skinGrad)">
      <animate attributeName="cy" values="228;226;228" dur="0.4s" repeatCount="indefinite" begin="0.15s"/>
    </circle>
  </g>
 
  <!-- Neck -->
  <rect x="350" y="128" width="16" height="18" fill="url(#skinGrad)" rx="4"/>
 
  <!-- Head (3/4 profile, looking at screen) -->
  <ellipse cx="358" cy="112" rx="26" ry="28" fill="url(#skinGrad)"/>
 
  <!-- Hair -->
  <path d="M332 100 Q335 78 358 74 Q382 72 378 98 Q372 82 358 80 Q340 82 332 100 Z" fill="#1a0f0a"/>
  <path d="M332 100 Q330 108 334 115 Q331 108 332 100 Z" fill="#1a0f0a"/>
 
  <!-- Ear -->
  <ellipse cx="332" cy="113" rx="5" ry="7" fill="#b87a52"/>
 
  <!-- Glasses -->
  <rect x="340" y="108" width="18" height="11" fill="none" stroke="#4a4a6a" stroke-width="1.5" rx="4" opacity="0.9"/>
  <rect x="360" y="108" width="16" height="11" fill="none" stroke="#4a4a6a" stroke-width="1.5" rx="4" opacity="0.9"/>
  <line x1="358" y1="112" x2="360" y2="112" stroke="#4a4a6a" stroke-width="1.5"/>
  <line x1="332" y1="113" x2="340" y2="112" stroke="#4a4a6a" stroke-width="1" opacity="0.6"/>
 
  <!-- Eye (partially visible) -->
  <ellipse cx="352" cy="113" rx="4" ry="3" fill="#0a0a15"/>
  <circle cx="353" cy="112" r="1" fill="white" opacity="0.6"/>
 
  <!-- Eyebrow -->
  <path d="M346 106 Q352 103 358 105" stroke="#1a0f0a" stroke-width="1.5" fill="none" stroke-linecap="round"/>
 
  <!-- Screen light reflection on face (subtle) -->
  <ellipse cx="345" cy="112" rx="14" ry="16" fill="#00d4ff" opacity="0.04"/>
 
  <!-- ===================== TEXT SECTION (right side) ===================== -->
 
  <!-- Decorative vertical line -->
  <line x1="540" y1="50" x2="540" y2="270" stroke="#00d4ff" stroke-width="0.5" opacity="0.3"/>
 
  <!-- Greeting text -->
  <text x="560" y="90" font-family="'Courier New', monospace" font-size="13" fill="#00d4ff" opacity="0.7">
    &gt; hello world
  </text>
 
  <!-- Main name with typewriter animation -->
  <text x="558" y="140" font-family="'Courier New', monospace" font-weight="700" font-size="36" fill="#ffffff" letter-spacing="1">
    <animate attributeName="opacity" values="0;1" dur="0.5s" fill="freeze" begin="0.3s"/>
    Lucas
  </text>
  <text x="558" y="178" font-family="'Courier New', monospace" font-weight="700" font-size="36" fill="#00d4ff" letter-spacing="1">
    <animate attributeName="opacity" values="0;1" dur="0.5s" fill="freeze" begin="0.7s"/>
    Manassés
  </text>
 
  <!-- Subtitle -->
  <text x="560" y="210" font-family="'Courier New', monospace" font-size="15" fill="#a0b4c8">
    <animate attributeName="opacity" values="0;1" dur="0.5s" fill="freeze" begin="1.1s"/>
    Full Stack Developer
  </text>
 
  <!-- Location + course badges -->
  <rect x="558" y="224" width="100" height="20" fill="#00d4ff" opacity="0.1" rx="10"/>
  <text x="608" y="238" font-family="'Courier New', monospace" font-size="10" fill="#00d4ff" text-anchor="middle">
    <animate attributeName="opacity" values="0;1" dur="0.5s" fill="freeze" begin="1.4s"/>
    Recife · PE
  </text>
 
  <rect x="668" y="224" width="105" height="20" fill="#7c3aed" opacity="0.15" rx="10"/>
  <text x="720" y="238" font-family="'Courier New', monospace" font-size="10" fill="#c084fc" text-anchor="middle">
    <animate attributeName="opacity" values="0;1" dur="0.5s" fill="freeze" begin="1.6s"/>
    ADS · 5° Período
  </text>
 
  <!-- Blinking cursor after name -->
  <rect x="780" y="162" width="3" height="22" fill="#00d4ff" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
 
  <!-- Decorative dots pattern (top right) -->
  <g opacity="0.15" fill="#00d4ff">
    <circle cx="855" cy="35" r="2"/>
    <circle cx="867" cy="35" r="2"/>
    <circle cx="879" cy="35" r="2"/>
    <circle cx="855" cy="47" r="2"/>
    <circle cx="867" cy="47" r="2"/>
    <circle cx="879" cy="47" r="2"/>
    <circle cx="855" cy="59" r="2"/>
    <circle cx="867" cy="59" r="2"/>
    <circle cx="879" cy="59" r="2"/>
  </g>
 
  <!-- Bottom wave decoration -->
  <path d="M0 290 Q225 270 450 285 Q675 300 900 280 L900 320 L0 320 Z" fill="#00d4ff" opacity="0.04"/>
  <path d="M0 300 Q225 285 450 295 Q675 308 900 295 L900 320 L0 320 Z" fill="#3b82f6" opacity="0.05"/>
 
  <!-- Bottom border line -->
  <line x1="0" y1="315" x2="900" y2="315" stroke="#00d4ff" stroke-width="0.5" opacity="0.2"/>
 
</svg>

# 👨🏻‍💻Lucas Manassés

**`Full Stack Developer`**

Olá, me chamo Lucas Manassés, tenho 20 anos de idade e sou desenvolvedor Full Stack. Estudante de Análise e Desenvolvimento de Sistemas pela UNIAMÉRICA/Descomplica. Facinado por tecnologia, especificamente por linguagens de programação, o que despertou em mim a curiosidade de entender como sistemas e aplicações funcionam.
Sou uma pessoa curiosa, com facilidade para aprender e grande vontade de adquirir novos conhecimentos. Gosto de desafios, de explorar novas tecnologias e estou constantemente buscando evoluir, tanto pessoal quanto profissionalmente, em desenvolvimento de software.

<p align="left">
    <a href="https://www.instagram.com/_lucas_manasses/">
        <img 
            alt="instagram" 
            title="siga-me no instagram" 
            src="https://custom-icon-badges.demolab.com/badge/Instagram-8A2BE2?logo=instagram&logoColor=white&style=for-the-badge"
        />
    </a>
    <a href="https://www.linkedin.com/in/lucasmanasses/">
        <img 
            alt="Linkedin" 
            title="Me siga no Linkedin" 
            src="https://custom-icon-badges.demolab.com/badge/LinkedIn-236ad3?style=for-the-badge&logo=linkedin&logoColor=white&color=236ad3"
        />
    </a>
    <a href="https://effortless-choux-0aef4e.netlify.app/">
        <img 
            alt="portfolio" 
            title="Acesse o meu Portfólio" 
            src="https://custom-icon-badges.demolab.com/badge/Portfólio-E1AD0E?style=for-the-badge&logo=briefcase&logoColor=white&color=E1AD0E"
        />
    </a>
     <a href="https://github.com/lucasmana">
        <img 
            alt="GitHub" 
            title="siga-me no Github" 
            src="https://custom-icon-badges.demolab.com/badge/GitHub-FF0000?style=for-the-badge&logo=github&logoColor=white"
        />
    </a> 
</p>

---


<img 
    align="left" 
    alt="HTML"
    title="HTML" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" 
/>
<img 
    align="left" 
    alt="CSS" 
    title="CSS"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" 
/>
<img 
    align="left" 
    alt="JavaScript" 
    title="JavaScript"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" 
/>
<img 
    align="left" 
    alt="TypeScript"
    title="TypeScript" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" 
/>
<img 
    align="left" 
    alt="React"
    title="React" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" 
/>
<img 
    align="left" 
    alt="Bootstrap"
    title="Bootstrap" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" 
/>
<img 
    align="left" 
    alt="PHP" 
    title="PHP"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" 
/>
<img 
    align="left" 
    alt="Git" 
    title="Git"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
/>
<img 
    align="left" 
    alt="Python" 
    title="Python"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" 
/>
<img 
    align="left" 
    alt="Node.js" 
    title="Node.js"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" 
/>
<img 
    align="left" 
    alt="MySQL" 
    title="MySQL"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" 
/>
<img 
    align="left" 
    alt="MongoDB" 
    title="MongoDB"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-plain.svg" 
/>
<img 
    align="left" 
    alt="XAMPP" 
    title="XAMPP"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apache/apache-original.svg" 
/>

<img 
    align="left" 
    alt="Docker" 
    title="Docker"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" 
/>







