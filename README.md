<svg viewBox="0 0 800 260" xmlns="http://www.w3.org/2000/svg" width="800" height="260">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Syne:wght@400;700;800&amp;display=swap');

      .bg { fill: #0d1117; }

      .name {
        font-family: 'Syne', sans-serif;
        font-size: 52px;
        font-weight: 800;
        fill: #e6edf3;
        opacity: 0;
        animation: fadeUp 0.8s cubic-bezier(0.22,1,0.36,1) 0.2s forwards;
      }
      .sub {
        font-family: 'Syne', sans-serif;
        font-size: 14px;
        font-weight: 400;
        fill: #8b949e;
        opacity: 0;
        animation: fadeUp 0.8s cubic-bezier(0.22,1,0.36,1) 0.6s forwards;
      }
      .tag {
        font-family: 'Syne', sans-serif;
        font-size: 12px;
        font-weight: 400;
        fill: #0d1117;
      }
      .section-label {
        font-family: 'Syne', sans-serif;
        font-size: 11px;
        font-weight: 700;
        fill: #8b949e;
        letter-spacing: 2px;
        opacity: 0;
        animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.6s forwards;
      }
      .currently {
        font-family: 'Syne', sans-serif;
        font-size: 13px;
        font-weight: 400;
        fill: #e6edf3;
      }

      .pill1 { fill: #3fb950; opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.0s forwards; }
      .pill2 { fill: #58a6ff; opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.2s forwards; }
      .pill3 { fill: #d29922; opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.4s forwards; }

      .t1 { opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.0s forwards; }
      .t2 { opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.2s forwards; }
      .t3 { opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.4s forwards; }

      .c1 { opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.8s forwards; }
      .c2 { opacity: 0; animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 2.1s forwards; }

      .line  { stroke: #21262d; stroke-width: 1; opacity: 0; animation: fadeIn 0.6s ease 0.5s  forwards; }
      .line2 { stroke: #21262d; stroke-width: 1; opacity: 0; animation: fadeIn 0.6s ease 1.55s forwards; }

      @keyframes fadeUp {
        from { opacity: 0; transform: translateY(10px); }
        to   { opacity: 1; transform: translateY(0); }
      }
      @keyframes fadeIn {
        to { opacity: 1; }
      }

      .dot {
        fill: #3fb950;
        animation: pulse 2.5s ease-in-out 2.5s infinite;
      }
      @keyframes pulse {
        0%, 100% { opacity: 1; }
        50%       { opacity: 0.25; }
      }

      .arrow { fill: #3fb950; opacity: 0; }
      .arrow.c1 { animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 1.8s forwards; }
      .arrow.c2 { animation: fadeUp 0.6s cubic-bezier(0.22,1,0.36,1) 2.1s forwards; }
    </style>
  </defs>

  <rect width="800" height="260" rx="12" class="bg"/>

  <!-- name + sub -->
  <text x="48" y="82" class="name">Satvik</text>
  <text x="50" y="108" class="sub">CS · BITS Pilani · 2028</text>

  <!-- divider 1 -->
  <line x1="48" y1="128" x2="752" y2="128" class="line"/>

  <!-- interest pills -->
  <rect x="48"  y="144" width="192" height="26" rx="13" class="pill1"/>
  <rect x="252" y="144" width="148" height="26" rx="13" class="pill2"/>
  <rect x="412" y="144" width="110" height="26" rx="13" class="pill3"/>

  <text x="144" y="162" text-anchor="middle" class="tag t1">Computational Neuroscience</text>
  <text x="326" y="162" text-anchor="middle" class="tag t2">Machine Learning</text>
  <text x="467" y="162" text-anchor="middle" class="tag t3">Data Science</text>

  <!-- divider 2 -->
  <line x1="48" y1="186" x2="752" y2="186" class="line2"/>

  <!-- currently label -->
  <text x="48" y="204" class="section-label">CURRENTLY</text>

  <!-- currently items -->
  <text x="48" y="224" class="currently c1">
    <tspan class="arrow c1">▸ </tspan>Contributing to Computational Neuroscience Research
  </text>
  <text x="48" y="246" class="currently c2">
    <tspan class="arrow c2">▸ </tspan>Exploring Quantitative Finance
  </text>

  <!-- pulse dot -->
  <circle cx="754" cy="157" r="4" class="dot"/>
</svg>

<!--
**vikysat/vikysat** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
