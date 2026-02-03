<!-- Background -->
<rect width="800" height="500" fill="url(#skyGradient)"/>

<!-- Stars -->
<circle cx="50" cy="30" r="1" fill="#ffffff" opacity="0.8">
  <animate attributeName="opacity" values="0.8;0.3;0.8" dur="3s" repeatCount="indefinite"/>
</circle>
<circle cx="150" cy="50" r="1.5" fill="#ffffff" opacity="0.6">
  <animate attributeName="opacity" values="0.6;0.9;0.6" dur="4s" repeatCount="indefinite"/>
</circle>
<circle cx="300" cy="20" r="1" fill="#ffffff" opacity="0.7"/>
<circle cx="450" cy="40" r="1.2" fill="#ffffff" opacity="0.5">
  <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
</circle>
<circle cx="600" cy="35" r="1" fill="#ffffff" opacity="0.8"/>
<circle cx="700" cy="25" r="1.3" fill="#ffffff" opacity="0.6">
  <animate attributeName="opacity" values="0.6;0.3;0.6" dur="3.5s" repeatCount="indefinite"/>
</circle>
<circle cx="250" cy="60" r="1" fill="#ffffff" opacity="0.7"/>
<circle cx="550" cy="55" r="1.1" fill="#ffffff" opacity="0.5"/>

<!-- Mountain ranges (back to front) -->
<!-- Far mountains -->
<path d="M0 400 L150 280 L300 320 L450 260 L600 300 L750 250 L800 280 L800 500 L0 500 Z" 
      fill="#0a1929" opacity="0.6"/>

<!-- Middle mountains -->
<path d="M0 450 L100 350 L200 320 L350 380 L500 300 L650 360 L800 320 L800 500 L0 500 Z" 
      fill="url(#mountainGradient)" opacity="0.8"/>

<!-- Front mountains with glow -->
<path d="M0 480 L120 380 L200 400 L300 340 L400 420 L550 360 L700 420 L800 380 L800 500 L0 500 Z" 
      fill="#16213e" filter="url(#glow)"/>

<!-- Matrix rain columns -->
<!-- Column 1 -->
<text x="50" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  ⛰<animate attributeName="y" from="-20" to="520" dur="6.2s" begin="0s" repeatCount="indefinite"/>
</text>
<text x="50" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  ▲<animate attributeName="y" from="-50" to="520" dur="6.2s" begin="0s" repeatCount="indefinite"/>
</text>
<text x="50" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  ∆<animate attributeName="y" from="-80" to="520" dur="6.2s" begin="0s" repeatCount="indefinite"/>
</text>
<text x="50" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ^<animate attributeName="y" from="-110" to="520" dur="6.2s" begin="0s" repeatCount="indefinite"/>
</text>
<text x="50" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  /\<animate attributeName="y" from="-140" to="520" dur="6.2s" begin="0s" repeatCount="indefinite"/>
</text>

<!-- Column 2 -->
<text x="150" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  🏔<animate attributeName="y" from="-20" to="520" dur="5.8s" begin="1.2s" repeatCount="indefinite"/>
</text>
<text x="150" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  ⛰<animate attributeName="y" from="-50" to="520" dur="5.8s" begin="1.2s" repeatCount="indefinite"/>
</text>
<text x="150" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  ▲<animate attributeName="y" from="-80" to="520" dur="5.8s" begin="1.2s" repeatCount="indefinite"/>
</text>
<text x="150" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ∆<animate attributeName="y" from="-110" to="520" dur="5.8s" begin="1.2s" repeatCount="indefinite"/>
</text>
<text x="150" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  ^<animate attributeName="y" from="-140" to="520" dur="5.8s" begin="1.2s" repeatCount="indefinite"/>
</text>

<!-- Column 3 -->
<text x="250" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  ▲<animate attributeName="y" from="-20" to="520" dur="7.1s" begin="2.4s" repeatCount="indefinite"/>
</text>
<text x="250" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  ⛰<animate attributeName="y" from="-50" to="520" dur="7.1s" begin="2.4s" repeatCount="indefinite"/>
</text>
<text x="250" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  🏔<animate attributeName="y" from="-80" to="520" dur="7.1s" begin="2.4s" repeatCount="indefinite"/>
</text>
<text x="250" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ∆<animate attributeName="y" from="-110" to="520" dur="7.1s" begin="2.4s" repeatCount="indefinite"/>
</text>
<text x="250" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  /\<animate attributeName="y" from="-140" to="520" dur="7.1s" begin="2.4s" repeatCount="indefinite"/>
</text>

<!-- Column 4 -->
<text x="350" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  🏔<animate attributeName="y" from="-20" to="520" dur="6.5s" begin="0.8s" repeatCount="indefinite"/>
</text>
<text x="350" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  ▲<animate attributeName="y" from="-50" to="520" dur="6.5s" begin="0.8s" repeatCount="indefinite"/>
</text>
<text x="350" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  ⛰<animate attributeName="y" from="-80" to="520" dur="6.5s" begin="0.8s" repeatCount="indefinite"/>
</text>
<text x="350" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ^<animate attributeName="y" from="-110" to="520" dur="6.5s" begin="0.8s" repeatCount="indefinite"/>
</text>
<text x="350" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  ∆<animate attributeName="y" from="-140" to="520" dur="6.5s" begin="0.8s" repeatCount="indefinite"/>
</text>

<!-- Column 5 -->
<text x="450" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  ∆<animate attributeName="y" from="-20" to="520" dur="5.3s" begin="3.1s" repeatCount="indefinite"/>
</text>
<text x="450" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  🏔<animate attributeName="y" from="-50" to="520" dur="5.3s" begin="3.1s" repeatCount="indefinite"/>
</text>
<text x="450" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  ▲<animate attributeName="y" from="-80" to="520" dur="5.3s" begin="3.1s" repeatCount="indefinite"/>
</text>
<text x="450" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ⛰<animate attributeName="y" from="-110" to="520" dur="5.3s" begin="3.1s" repeatCount="indefinite"/>
</text>
<text x="450" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  ^<animate attributeName="y" from="-140" to="520" dur="5.3s" begin="3.1s" repeatCount="indefinite"/>
</text>

<!-- Column 6 -->
<text x="550" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  ⛰<animate attributeName="y" from="-20" to="520" dur="6.9s" begin="1.8s" repeatCount="indefinite"/>
</text>
<text x="550" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  ∆<animate attributeName="y" from="-50" to="520" dur="6.9s" begin="1.8s" repeatCount="indefinite"/>
</text>
<text x="550" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  🏔<animate attributeName="y" from="-80" to="520" dur="6.9s" begin="1.8s" repeatCount="indefinite"/>
</text>
<text x="550" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ▲<animate attributeName="y" from="-110" to="520" dur="6.9s" begin="1.8s" repeatCount="indefinite"/>
</text>
<text x="550" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  /\<animate attributeName="y" from="-140" to="520" dur="6.9s" begin="1.8s" repeatCount="indefinite"/>
</text>

<!-- Column 7 -->
<text x="650" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  🏔<animate attributeName="y" from="-20" to="520" dur="5.6s" begin="2.7s" repeatCount="indefinite"/>
</text>
<text x="650" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  ⛰<animate attributeName="y" from="-50" to="520" dur="5.6s" begin="2.7s" repeatCount="indefinite"/>
</text>
<text x="650" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  ▲<animate attributeName="y" from="-80" to="520" dur="5.6s" begin="2.7s" repeatCount="indefinite"/>
</text>
<text x="650" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ∆<animate attributeName="y" from="-110" to="520" dur="5.6s" begin="2.7s" repeatCount="indefinite"/>
</text>
<text x="650" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  ^<animate attributeName="y" from="-140" to="520" dur="5.6s" begin="2.7s" repeatCount="indefinite"/>
</text>

<!-- Column 8 -->
<text x="750" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="1.0" filter="url(#glow)">
  ▲<animate attributeName="y" from="-20" to="520" dur="6.7s" begin="0.5s" repeatCount="indefinite"/>
</text>
<text x="750" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.8">
  🏔<animate attributeName="y" from="-50" to="520" dur="6.7s" begin="0.5s" repeatCount="indefinite"/>
</text>
<text x="750" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.6">
  ⛰<animate attributeName="y" from="-80" to="520" dur="6.7s" begin="0.5s" repeatCount="indefinite"/>
</text>
<text x="750" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.4">
  ∆<animate attributeName="y" from="-110" to="520" dur="6.7s" begin="0.5s" repeatCount="indefinite"/>
</text>
<text x="750" y="-20" fill="#00ff41" font-family="monospace" font-size="14" opacity="0.2">
  /\<animate attributeName="y" from="-140" to="520" dur="6.7s" begin="0.5s" repeatCount="indefinite"/>
</text>

<!-- Central title text with glowing effect -->
<text x="400" y="250" font-family="monospace" font-size="48" fill="#00ff41" 
      text-anchor="middle" font-weight="bold" filter="url(#glow)">
  SIMANGKA
  <animate attributeName="opacity" values="1;0.7;1" dur="2s" repeatCount="indefinite"/>
</text>

<text x="400" y="290" font-family="monospace" font-size="20" fill="#00cc33" 
      text-anchor="middle" opacity="0.9">
  ~ Mountain Code Explorer ~
</text>
