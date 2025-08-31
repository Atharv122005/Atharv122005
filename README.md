<?xml version="1.0" encoding="utf-8"?>
<svg xmlns="http://www.w3.org/2000/svg"
     width="900" height="220" viewBox="0 0 900 220" role="img" aria-label="ahi atharv typing animation">
  <defs>
    <!-- Colorful gradient for the text -->
    <linearGradient id="grad" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#ff6b6b"/>
      <stop offset="40%" stop-color="#ffd166"/>
      <stop offset="70%" stop-color="#6a4c93"/>
      <stop offset="100%" stop-color="#1dd3b0"/>
    </linearGradient>

    <!-- Soft glow -->
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="100%" height="100%" rx="14" fill="#0f172a"/> <!-- dark background -->

  <g transform="translate(40,140)">
    <!-- common text style -->
    <style>
      .letter { font-family: 'Poppins', 'Segoe UI', Arial, sans-serif; font-weight: 800; font-size: 84px; fill: url(#grad); filter: url(#glow); }
      .shadow { fill: rgba(0,0,0,0.35); font-weight:800; font-size:84px; }
    </style>

    <!-- We'll render each letter in its own group so we can animate them separately.
         Adjust the 'begin' times to slow/speed the typing. -->

    <!-- letter 1: a -->
    <g transform="translate(0,0)" >
      <text class="shadow" x="6" y="6">a</text>
      <text class="letter" x="0" y="0">a
        <animate attributeName="opacity" from="0" to="1" begin="0s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="0s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- letter 2: h -->
    <g transform="translate(70,0)">
      <text class="shadow" x="6" y="6">h</text>
      <text class="letter" x="0" y="0">h
        <animate attributeName="opacity" from="0" to="1" begin="0.55s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="0.55s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- letter 3: i -->
    <g transform="translate(140,0)">
      <text class="shadow" x="6" y="6">i</text>
      <text class="letter" x="0" y="0">i
        <animate attributeName="opacity" from="0" to="1" begin="1.1s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="1.1s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- small gap -->
    <!-- letter 4: (space, so we just reserve x) -->

    <!-- letter 5: a (second word) -->
    <g transform="translate(240,0)">
      <text class="shadow" x="6" y="6">a</text>
      <text class="letter" x="0" y="0">a
        <animate attributeName="opacity" from="0" to="1" begin="1.85s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="1.85s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- letter 6: t -->
    <g transform="translate(310,0)">
      <text class="shadow" x="6" y="6">t</text>
      <text class="letter" x="0" y="0">t
        <animate attributeName="opacity" from="0" to="1" begin="2.4s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="2.4s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- letter 7: h -->
    <g transform="translate(380,0)">
      <text class="shadow" x="6" y="6">h</text>
      <text class="letter" x="0" y="0">h
        <animate attributeName="opacity" from="0" to="1" begin="2.95s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="2.95s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- letter 8: a -->
    <g transform="translate(450,0)">
      <text class="shadow" x="6" y="6">a</text>
      <text class="letter" x="0" y="0">a
        <animate attributeName="opacity" from="0" to="1" begin="3.5s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="3.5s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- letter 9: r -->
    <g transform="translate(520,0)">
      <text class="shadow" x="6" y="6">r</text>
      <text class="letter" x="0" y="0">r
        <animate attributeName="opacity" from="0" to="1" begin="4.05s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="4.05s" dur="0.45s" fill="freeze"/>
      </text>
    </g>

    <!-- letter 10: v -->
    <g transform="translate(590,0)">
      <text class="shadow" x="6" y="6">v</text>
      <text class="letter" x="0" y="0">v
        <animate attributeName="opacity" from="0" to="1" begin="4.6s" dur="0.45s" fill="freeze"/>
        <animateTransform attributeName="transform" attributeType="XML"
                          type="scale" values="0.6;1.12;1" keyTimes="0;0.6;1"
                          begin="4.6s" dur="0.45s" fill="freeze"/>
      </text>
    </g>
  </g>

  <!-- optional caption below -->
  <text x="50" y="200" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#9aa4bf">
    slow-motion typing animation — "ahi atharv"
  </text>
</svg>
