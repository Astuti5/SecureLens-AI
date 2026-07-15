<svg width="1280" height="640" viewBox="0 0 1280 640" xmlns="http://www.w3.org/2000/svg" role="img">
<title>SecureLens AI — Privacy-First On-Device AI Security Assistant</title>
<defs>
  <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%" stop-color="#05070A"/>
    <stop offset="45%" stop-color="#0B1220"/>
    <stop offset="100%" stop-color="#05070A"/>
  </linearGradient>

  <radialGradient id="centerGlow" cx="50%" cy="42%" r="55%">
    <stop offset="0%" stop-color="#00C2FF" stop-opacity="0.16"/>
    <stop offset="55%" stop-color="#00C2FF" stop-opacity="0.05"/>
    <stop offset="100%" stop-color="#00C2FF" stop-opacity="0"/>
  </radialGradient>

  <linearGradient id="shieldGrad" x1="0%" y1="0%" x2="0%" y2="100%">
    <stop offset="0%" stop-color="#5FE3FF"/>
    <stop offset="100%" stop-color="#00C2FF"/>
  </linearGradient>

  <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="#FFFFFF"/>
    <stop offset="100%" stop-color="#CFEFFF"/>
  </linearGradient>

  <pattern id="hexGrid" width="56" height="97" patternUnits="userSpaceOnUse" patternTransform="translate(0,0)">
    <path d="M28 0 L56 16 L56 48 L28 64 L0 48 L0 16 Z" fill="none" stroke="#1D9E75" stroke-opacity="0.06" stroke-width="1"/>
    <path d="M28 33 L56 49 L56 81 L28 97 L0 81 L0 49 Z" fill="none" stroke="#00C2FF" stroke-opacity="0.05" stroke-width="1"/>
  </pattern>

  <filter id="softGlow" x="-60%" y="-60%" width="220%" height="220%">
    <feGaussianBlur stdDeviation="6" result="blur"/>
    <feMerge>
      <feMergeNode in="blur"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>

  <filter id="panelBlur" x="-20%" y="-20%" width="140%" height="140%">
    <feGaussianBlur stdDeviation="18"/>
  </filter>

  <style>
    @keyframes pulse { 0%,100% { opacity: 0.15; } 50% { opacity: 0.55; } }
    @keyframes twinkle { 0%,100% { opacity: 0.1; } 50% { opacity: 0.8; } }
    @keyframes drift { 0% { transform: translateY(0px); } 50% { transform: translateY(-8px); } 100% { transform: translateY(0px); } }
    @keyframes dashflow { to { stroke-dashoffset: -200; } }
    @keyframes shieldPulse { 0%,100% { opacity: 0.55; } 50% { opacity: 1; } }
    .node { animation: pulse 4s ease-in-out infinite; }
    .particle { animation: twinkle 3.4s ease-in-out infinite; }
    .float { animation: drift 6s ease-in-out infinite; }
    .stream { stroke-dasharray: 6 10; animation: dashflow 3.5s linear infinite; }
    .stream2 { stroke-dasharray: 4 14; animation: dashflow 5s linear infinite; }
    .shieldRing { animation: shieldPulse 2.6s ease-in-out infinite; }
    text { font-family: -apple-system, 'Segoe UI', Helvetica, Arial, sans-serif; }
  </style>
</defs>

<rect width="1280" height="640" fill="url(#bgGrad)"/>
<rect width="1280" height="640" fill="url(#hexGrid)"/>
<rect width="1280" height="640" fill="url(#centerGlow)"/>

<g stroke="#00C2FF" stroke-width="1" fill="none" opacity="0.5">
  <path class="stream" d="M-20 120 C 260 60, 420 220, 700 140 S 1180 60, 1320 140"/>
  <path class="stream2" d="M-20 520 C 300 600, 520 420, 760 520 S 1100 600, 1320 500" stroke="#1D9E75"/>
  <path class="stream" d="M-20 340 C 220 280, 360 420, 640 340" opacity="0.35"/>
</g>

<g fill="#00C2FF">
  <g class="node"><circle cx="150" cy="140" r="3"/></g>
  <g class="node" style="animation-delay:.5s"><circle cx="230" cy="90" r="2.5"/></g>
  <g class="node" style="animation-delay:1s"><circle cx="120" cy="260" r="2.5"/></g>
  <g class="node" style="animation-delay:1.4s"><circle cx="1080" cy="150" r="3"/></g>
  <g class="node" style="animation-delay:.8s"><circle cx="1150" cy="240" r="2.5"/></g>
  <g class="node" style="animation-delay:2s"><circle cx="1000" cy="320" r="2.5"/></g>
  <g class="node" style="animation-delay:.3s"><circle cx="220" cy="480" r="3"/></g>
  <g class="node" style="animation-delay:1.6s"><circle cx="1120" cy="460" r="3"/></g>
</g>
<g stroke="#00C2FF" stroke-width="0.6" opacity="0.18">
  <line x1="150" y1="140" x2="230" y2="90"/>
  <line x1="150" y1="140" x2="120" y2="260"/>
  <line x1="1080" y1="150" x2="1150" y2="240"/>
  <line x1="1080" y1="150" x2="1000" y2="320"/>
  <line x1="220" y1="480" x2="120" y2="260"/>
  <line x1="1120" y1="460" x2="1000" y2="320"/>
</g>

<g fill="#5FE3FF" opacity="0.5">
  <circle class="particle" cx="90" cy="400" r="1.6"/>
  <circle class="particle" cx="340" cy="60" r="1.4" style="animation-delay:.6s"/>
  <circle class="particle" cx="600" cy="580" r="1.5" style="animation-delay:1.2s"/>
  <circle class="particle" cx="960" cy="70" r="1.4" style="animation-delay:1.8s"/>
  <circle class="particle" cx="1200" cy="380" r="1.6" style="animation-delay:.9s"/>
  <circle class="particle" cx="60" cy="560" r="1.4" style="animation-delay:2.1s"/>
  <circle class="particle" cx="1230" cy="560" r="1.5" style="animation-delay:1.5s"/>
  <circle class="particle" cx="700" cy="40" r="1.3" style="animation-delay:.3s"/>
</g>

<g opacity="0.16" stroke="#8FEFDD" fill="none">
  <g class="float">
    <rect x="60" y="72" width="86" height="56" rx="6" stroke-width="1.4"/>
    <line x1="60" y1="88" x2="146" y2="88" stroke-width="1"/>
    <circle cx="70" cy="80" r="2" fill="#8FEFDD" stroke="none"/>
    <circle cx="78" cy="80" r="2" fill="#8FEFDD" stroke="none"/>
    <circle cx="86" cy="80" r="2" fill="#8FEFDD" stroke="none"/>
  </g>
</g>

<g opacity="0.18" transform="translate(96,210)">
  <g stroke="#00C2FF" fill="none">
    <rect x="-20" y="-20" width="40" height="40" rx="4" stroke-width="1.4"/>
    <rect x="-9" y="-9" width="18" height="18" rx="2" stroke-width="1.2"/>
    <line x1="-20" y1="-10" x2="-30" y2="-10" stroke-width="1"/>
    <line x1="-20" y1="10" x2="-30" y2="10" stroke-width="1"/>
    <line x1="20" y1="-10" x2="30" y2="-10" stroke-width="1"/>
    <line x1="20" y1="10" x2="30" y2="10" stroke-width="1"/>
    <line x1="-10" y1="-20" x2="-10" y2="-30" stroke-width="1"/>
    <line x1="10" y1="-20" x2="10" y2="-30" stroke-width="1"/>
    <line x1="-10" y1="20" x2="-10" y2="30" stroke-width="1"/>
    <line x1="10" y1="20" x2="10" y2="30" stroke-width="1"/>
  </g>
  <animateTransform attributeName="transform" type="rotate" from="0 96 210" to="360 96 210" dur="26s" repeatCount="indefinite" additive="sum"/>
</g>

<g opacity="0.2" transform="translate(100,350)">
  <g stroke="#1D9E75" fill="none" stroke-width="1.3">
    <path d="M0,-16 L14,-8 L14,8 L0,16 L-14,8 L-14,-8 Z"/>
    <path d="M0,-16 L0,0 L14,8 M0,0 L-14,8"/>
  </g>
</g>

<g opacity="0.2" fill="none" stroke="#5FE3FF" stroke-width="1.4" transform="translate(104,470)">
  <rect x="-12" y="-2" width="24" height="18" rx="3"/>
  <path d="M-8,-2 v-6 a8,8 0 0 1 16,0 v6"/>
</g>

<g opacity="0.16" stroke="#00C2FF" fill="none" stroke-width="1.2" transform="translate(100,575)">
  <circle r="20"/>
  <circle r="12"/>
  <circle r="4" fill="#00C2FF" stroke="none"/>
  <path d="M-20,0 H20 M0,-20 V20"/>
</g>

<g opacity="0.18" fill="none" stroke="#5FE3FF" stroke-width="1.3">
  <g transform="translate(1178,110)">
    <rect x="-16" y="-16" width="32" height="32" rx="2"/>
    <rect x="-11" y="-11" width="8" height="8" fill="#5FE3FF" stroke="none"/>
    <rect x="3" y="-11" width="8" height="8" fill="#5FE3FF" stroke="none"/>
    <rect x="-11" y="3" width="8" height="8" fill="#5FE3FF" stroke="none"/>
    <rect x="3" y="4" width="3" height="3" fill="#5FE3FF" stroke="none"/>
    <rect x="9" y="4" width="3" height="3" fill="#5FE3FF" stroke="none"/>
    <rect x="3" y="9" width="3" height="3" fill="#5FE3FF" stroke="none"/>
  </g>
</g>

<g opacity="0.2" transform="translate(1176,230)">
  <g stroke="#00C2FF" fill="none" stroke-width="1.3">
    <ellipse rx="26" ry="10"/>
    <ellipse rx="26" ry="10" transform="rotate(60)"/>
    <ellipse rx="26" ry="10" transform="rotate(120)"/>
    <circle r="3.4" fill="#00C2FF" stroke="none"/>
  </g>
  <animateTransform attributeName="transform" type="rotate" from="0 1176 230" to="360 1176 230" dur="20s" repeatCount="indefinite" additive="sum"/>
</g>

<g opacity="0.22" stroke="#F2C265" fill="none" stroke-width="1.3" transform="translate(1180,350)">
  <path d="M0,-16 L14,10 H-14 Z" stroke-linejoin="round"/>
  <line x1="0" y1="-5" x2="0" y2="3" stroke-linecap="round"/>
  <circle cx="0" cy="7" r="0.8" fill="#F2C265" stroke="none"/>
</g>

<g opacity="0.2" stroke="#5FE3FF" fill="none" stroke-width="1.3" transform="translate(1178,468)">
  <path d="M-18,4 A18,18 0 0 1 18,4"/>
  <line x1="0" y1="4" x2="10" y2="-10"/>
  <circle r="2.4" fill="#5FE3FF" stroke="none"/>
</g>

<g opacity="0.18" stroke="#8FEFDD" fill="none" stroke-width="1.3" transform="translate(1178,568)">
  <rect x="-16" y="-11" width="32" height="20" rx="4"/>
  <path d="M-16,-9 L0,3 L16,-9"/>
</g>

<g opacity="0.16" stroke="#1D9E75" fill="none" stroke-width="1.2" transform="translate(940,44)">
  <circle r="9"/>
  <path d="M-9,0 h18 M0,-9 v18 M-6,-6 a12,12 0 0 0 12,12 M6,6 a12,12 0 0 0 -12,-12"/>
</g>

<g opacity="0.18" fill="none" stroke="#5FE3FF" stroke-width="1.3" transform="translate(300,606)">
  <path d="M-13,7 a9,9 0 0 1 9,-16 h6 a9,9 0 0 1 0,18 h-9 l-6,5 v-5 z"/>
</g>

<g filter="url(#panelBlur)" opacity="0.35">
  <rect x="260" y="90" width="760" height="470" rx="26" fill="#00C2FF" opacity="0.05"/>
</g>
<rect x="260" y="90" width="760" height="470" rx="26" fill="#0F1B2E" fill-opacity="0.35" stroke="#2A9FCB" stroke-opacity="0.35" stroke-width="1"/>

<g class="shieldRing" filter="url(#softGlow)" transform="translate(640,168)">
  <path d="M0,-44 L38,-28 V6 C38,34 20,52 0,60 C-20,52 -38,34 -38,6 V-28 Z" fill="url(#shieldGrad)" opacity="0.95"/>
  <path d="M0,-44 L38,-28 V6 C38,34 20,52 0,60 C-20,52 -38,34 -38,6 V-28 Z" fill="none" stroke="#FFFFFF" stroke-opacity="0.5" stroke-width="1.2"/>
  <rect x="-13" y="0" width="26" height="20" rx="4" fill="#05202B"/>
  <path d="M-8,0 v-8 a8,8 0 0 1 16,0 v8" fill="none" stroke="#05202B" stroke-width="4"/>
  <circle cx="0" cy="10" r="2.6" fill="#5FE3FF"/>
</g>

<text x="640" y="292" text-anchor="middle" font-size="46" font-weight="700" fill="url(#titleGrad)" letter-spacing="1">SecureLens AI</text>

<text x="640" y="330" text-anchor="middle" font-size="19" fill="#B9D8E8" opacity="0.9">Privacy-First On-Device AI Security Assistant</text>

<text x="640" y="366" text-anchor="middle" font-size="14" fill="#5FE3FF" letter-spacing="3" opacity="0.9">DETECT &#8226; EXPLAIN &#8226; PROTECT</text>

<g font-size="13" font-weight="500">
  <g transform="translate(300,420)">
    <rect width="178" height="40" rx="20" fill="#0E2230" stroke="#1F6E86" stroke-width="1"/>
    <text x="20" y="25" fill="#5FE3FF">&#10003;</text>
    <text x="38" y="25" fill="#E7F6FB">On-Device AI</text>
  </g>
  <g transform="translate(490,420)">
    <rect width="150" height="40" rx="20" fill="#0E2230" stroke="#1F6E86" stroke-width="1"/>
    <text x="20" y="25" fill="#5FE3FF">&#10003;</text>
    <text x="38" y="25" fill="#E7F6FB">Browser AI</text>
  </g>
  <g transform="translate(652,420)">
    <rect width="160" height="40" rx="20" fill="#0E2230" stroke="#1F6E86" stroke-width="1"/>
    <text x="20" y="25" fill="#5FE3FF">&#10003;</text>
    <text x="38" y="25" fill="#E7F6FB">Privacy First</text>
  </g>
  <g transform="translate(340,472)">
    <rect width="160" height="40" rx="20" fill="#0E2230" stroke="#1F6E86" stroke-width="1"/>
    <text x="20" y="25" fill="#5FE3FF">&#10003;</text>
    <text x="38" y="25" fill="#E7F6FB">Open Source</text>
  </g>
  <g transform="translate(512,472)">
    <rect width="178" height="40" rx="20" fill="#0E2230" stroke="#1F6E86" stroke-width="1"/>
    <text x="20" y="25" fill="#5FE3FF">&#10003;</text>
    <text x="38" y="25" fill="#E7F6FB">Explainable AI</text>
  </g>
  <g transform="translate(702,472)">
    <rect width="168" height="40" rx="20" fill="#0E2230" stroke="#1F6E86" stroke-width="1"/>
    <text x="20" y="25" fill="#5FE3FF">&#10003;</text>
    <text x="38" y="25" fill="#E7F6FB">Offline Ready</text>
  </g>
</g>

<text x="640" y="536" text-anchor="middle" font-size="12" fill="#5C7E92" opacity="0.8" letter-spacing="1">OPEN SOURCE &#8226; MIT LICENSED &#8226; BUILT FOR PRIVACY</text>
</svg>
