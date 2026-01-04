<div align="center">

<!-- 애니메이션 SVG 타이틀 -->
<svg width="650" height="180" xmlns="http://www.w3.org/2000/svg">
  <style>
    @keyframes pulse {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.7; }
    }
    @keyframes glow {
      0%, 100% { filter: drop-shadow(0 0 5px #FF00FF); }
      50% { filter: drop-shadow(0 0 15px #00FFFF); }
    }
    .pulse { animation: pulse 2s infinite; }
    .glow { animation: glow 3s infinite; }
  </style>
  
  <defs>
    <linearGradient id="cyber-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#FF00FF" />
      <stop offset="50%" stop-color="#00FFFF" />
      <stop offset="100%" stop-color="#FF00FF" />
    </linearGradient>
    
    <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="rgba(255,0,255,0.2)" stroke-width="1"/>
    </pattern>
  </defs>
  
  <!-- 배경 -->
  <rect x="5" y="5" width="640" height="170" rx="25" fill="rgba(10,10,20,0.85)" stroke="url(#cyber-gradient)" stroke-width="4"/>
  <rect x="10" y="10" width="630" height="160" rx="20" fill="url(#grid)"/>
  
  <!-- 왼쪽 디지털 패널 -->
  <rect x="25" y="25" width="150" height="130" rx="15" fill="rgba(0,0,0,0.6)" stroke="#00FFFF" stroke-width="2"/>
  
  <!-- 로켓 애니메이션 -->
  <text x="100" y="85" class="pulse" fill="url(#cyber-gradient)" font-size="50" font-weight="bold" text-anchor="middle">🚀</text>
  
  <!-- 메인 타이틀 -->
  <g class="glow">
    <text x="230" y="75" fill="#FFFFFF" font-family="'Orbitron', monospace" font-size="32" font-weight="900">
      VISIT MY
    </text>
    <text x="230" y="110" fill="url(#cyber-gradient)" font-family="'Orbitron', monospace" font-size="38" font-weight="900">
      PORTFOLIO
    </text>
  </g>
  
  <!-- 한국어 서브타이틀 -->
  <text x="230" y="140" fill="#FF99FF" font-family="'Apple SD Gothic Neo', sans-serif" font-size="18" font-weight="bold">
    포트폴리오 방문하기
  </text>
  
  <!-- 오른쪽 네온 바 -->
  <rect x="520" y="40" width="8" height="100" rx="4" fill="url(#cyber-gradient)">
    <animate attributeName="height" values="100;130;100" dur="2s" repeatCount="indefinite"/>
  </rect>
  
  <!-- 디지털 코드 효과 -->
  <text x="580" y="50" fill="#00FFFF" font-family="monospace" font-size="12">01001000</text>
  <text x="580" y="70" fill="#FF00FF" font-family="monospace" font-size="12">01101001</text>
  <text x="580" y="90" fill="#00FFFF" font-family="monospace" font-size="12">00101110</text>
</svg>

</div>
