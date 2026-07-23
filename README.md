<div align="center">

<!-- Animated Header SVG -->
<svg width="800" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="coffeeGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#3C1518;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#69306D;stop-opacity:1">
        <animate attributeName="stop-color" values="#69306D;#6B4226;#69306D" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#6B4226;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Steam Animation -->
    <filter id="turbulence">
      <feTurbulence type="fractalNoise" baseFrequency="0.015" numOctaves="3" result="noise">
        <animate attributeName="baseFrequency" values="0.015;0.025;0.015" dur="5s" repeatCount="indefinite"/>
      </feTurbulence>
      <feDisplacementMap in="SourceGraphic" in2="noise" scale="8" />
    </filter>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" rx="20" fill="#1A0E0A"/>
  <rect width="800" height="200" rx="20" fill="url(#coffeeGrad)" opacity="0.3"/>
    <!-- Coffee-Themed Shields.io Badges -->
  <p align="center">
    <img src="https://img.shields.io/badge/Roast-Dark%20%26%20Smooth-3B2219?style=for-the-badge&logo=coffeescript&logoColor=D2B48C" alt="Roast" />
    <img src="https://img.shields.io/badge/Status-Freshly%20Brewed-6F4E37?style=for-the-badge&logo=target&logoColor=F5EBE0" alt="Status" />
    <img src="https://img.shields.io/badge/Version-v2.4.0-C68B59?style=for-the-badge&logo=git&logoColor=white" alt="Version" />
    <img src="https://img.shields.io/badge/License-MIT-8D4925?style=for-the-badge" alt="License" />
  </p>
