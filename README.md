from pathlib import Path

base = Path("/mnt/data/github_readme_design")
base.mkdir(exist_ok=True)

# Custom SVG banner / visual panels that GitHub can render from a repository-relative path.
svg = r'''<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="250" viewBox="0 0 1200 250">
<defs>
  <linearGradient id="bg" x1="0" x2="1" y1="0" y2="1">
    <stop offset="0" stop-color="#070912"/><stop offset="1" stop-color="#111329"/>
  </linearGradient>
  <linearGradient id="purple" x1="0" x2="1">
    <stop offset="0" stop-color="#7c3aed"/><stop offset="1" stop-color="#c084fc"/>
  </linearGradient>
  <filter id="glow"><feGaussianBlur stdDeviation="5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
</defs>
<rect width="1200" height="250" rx="22" fill="url(#bg)" stroke="#30205d"/>
<circle cx="105" cy="125" r="72" fill="#15102a" stroke="#a970ff" stroke-width="3" filter="url(#glow)"/>
<text x="105" y="112" fill="#c084fc" font-size="48" text-anchor="middle" font-family="monospace">&lt;/&gt;</text>
<text x="105" y="145" fill="#fff" font-size="14" text-anchor="middle" font-family="sans-serif">BUILDER</text>
<text x="220" y="82" fill="#fff" font-size="38" font-weight="700" font-family="monospace">SAHAN KUMAR ⚡</text>
<text x="220" y="120" fill="#b78cff" font-size="20" font-family="sans-serif">Developer • Builder • Problem Solver</text>
<text x="220" y="158" fill="#cbd0e1" font-size="16" font-family="sans-serif">Full Stack Developer  |  AI Enthusiast  |  Open Source Builder</text>
<text x="220" y="198" fill="#8b7ca8" font-size="15" font-style="italic" font-family="sans-serif">“Always learning. Always shipping.”</text>
<rect x="925" y="45" width="215" height="160" rx="16" fill="#0b0e19" stroke="#55308d"/>
<text x="955" y="82" fill="#c084fc" font-size="15" font-family="monospace">CURRENT MODE</text>
<text x="955" y="118" fill="#fff" font-size="23" font-family="monospace">BUILDING</text>
<text x="955" y="147" fill="#9aa2bb" font-size="14" font-family="sans-serif">AI • Web • Linux</text>
<text x="955" y="174" fill="#9aa2bb" font-size="14" font-family="sans-serif">Games • Systems</text>
</svg>'''
(base / "banner.svg").write_text(svg, encoding="utf-8")

readme = r'''<div align="center">

<img src="./github_readme_design/banner.svg" width="100%" alt="Sahan Kumar GitHub banner">

<br>

<table>
<tr>
<td align="center" bgcolor="#0b0e19">

### ⚡ DEVELOPER • BUILDER • PROBLEM SOLVER

**Building ideas into real-world products.**

`AI / ML` · `Full Stack` · `Local LLMs` · `Linux` · `Cybersecurity` · `3D`

<br>

[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sahankumar6699-dev)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/)

</td>
</tr>
</table>

</div>

---

<table>
<tr>

<td width="27%" valign="top" bgcolor="#080b14">

## 👤 SAHAN KUMAR

> **Developer • Builder • Problem Solver**

📍 **Mangalore, India**

🎓 **Sahyadri College of Engineering & Management**  
CSE — **AI & ML**

### 🚀 CURRENTLY BUILDING

🔮 **Nightshift AI**  
Local AI agent platform

🐧 **RobinhoodOS**  
Custom Linux OS

🏎️ **NeonDrive**  
Web 3D driving game

⬇️ **Dropforge**  
Video utility platform

🧮 **Kalcio**  
Smart calculator

<br>

### 💬 PHILOSOPHY

> *“Building in the dark, so I can shine in the daylight.”*

</td>

<td width="73%" valign="top">

<table>
<tr>
<td bgcolor="#0d101c">

## 🧰 TECH STACK & SKILLS

</td>
</tr>
</table>

<table>
<tr>
<td valign="top" bgcolor="#0a0d17">

### 🌐 FRONTEND

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)  
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)  
![Next](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js)  
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</td>
<td valign="top" bgcolor="#0a0d17">

### ⚙️ BACKEND

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)  
![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)  
![Express](https://img.shields.io/badge/Express-000?style=flat-square&logo=express)  
![REST](https://img.shields.io/badge/REST_APIs-555?style=flat-square)  
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

</td>
<td valign="top" bgcolor="#0a0d17">

### ☁️ DATA / CLOUD

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)  
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)  
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel)  
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

</td>
</tr>

<tr>
<td valign="top" bgcolor="#0a0d17">

### 🧰 TOOLS

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)  
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode)  
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite)  
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm)

</td>
<td valign="top" bgcolor="#0a0d17">

### 🤖 AI / LLM

![Ollama](https://img.shields.io/badge/Ollama-000?style=flat-square)  
![LM Studio](https://img.shields.io/badge/LM_Studio-7C3AED?style=flat-square)  
![Qwen](https://img.shields.io/badge/Qwen3-6B4EFF?style=flat-square)  
![Agents](https://img.shields.io/badge/AI_Agents-A970FF?style=flat-square)  
![Local AI](https://img.shields.io/badge/Local_AI-8B5CF6?style=flat-square)

</td>
<td valign="top" bgcolor="#0a0d17">

### 🧩 OTHER

![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender)  
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godot-engine)  
![Kali](https://img.shields.io/badge/Kali-557C94?style=flat-square&logo=kalilinux)  
![Termux](https://img.shields.io/badge/Termux-000?style=flat-square&logo=termux)

🔐 Ethical Hacking  
🔎 OSINT  
🧠 Problem Solving

</td>
</tr>
</table>

---

<table>
<tr>
<td bgcolor="#0d101c">

## 🚀 FEATURED PROJECTS

</td>
</tr>
</table>

<table>
<tr>

<td valign="top" bgcolor="#0a0d17">

### 🤖 Nightshift AI

Local AI agents designed to work autonomously and build while you sleep.

`Python` `Ollama` `LLM` `AI Agents`

</td>

<td valign="top" bgcolor="#0a0d17">

### 🐧 RobinhoodOS

Custom Linux OS experiment with a local AI assistant and custom UX.

`Linux` `Live-build` `Bash` `Local AI`

</td>

<td valign="top" bgcolor="#0a0d17">

### 🏎️ NeonDrive

Interactive browser-based 3D driving game.

`Three.js` `Vite` `JavaScript`

</td>

</tr>

<tr>

<td valign="top" bgcolor="#0a0d17">

### ⬇️ Dropforge

Video utility platform concept with automatic platform detection and bulk downloading.

`Next.js` `Node.js` `FFmpeg`

</td>

<td valign="top" bgcolor="#0a0d17">

### 🧮 Kalcio

Modern calculator concept with scientific and utility-focused features.

`JavaScript` `HTML` `CSS`

</td>

<td valign="top" bgcolor="#0a0d17">

### 🎮 Project Genesis

A Minecraft-inspired game experiment focused on mobile players.

`Godot` `GDScript` `Game Dev`

</td>

</tr>
</table>

---

<table>
<tr>
<td bgcolor="#0d101c">

## 📊 GITHUB STATS

</td>
</tr>
</table>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sahankumar6699-dev&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A970FF&icon_color=A970FF&text_color=E6E8F0" height="170">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahankumar6699-dev&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A970FF&text_color=E6E8F0" height="170">

<br>

<img src="https://streak-stats.demolab.com?user=sahankumar6699-dev&theme=tokyonight&hide_border=true&background=0D1117&ring=A970FF&fire=A970FF&currStreakLabel=A970FF">

</div>

---

<table>
<tr>
<td width="50%" valign="top" bgcolor="#0a0d17">

## 🔥 CURRENT FOCUS

- 🤖 Local autonomous AI agents
- 🧠 AI / ML & LLM engineering
- 💻 Full-stack development
- 🐧 Operating-system development
- 🎮 Game development
- 🔐 Ethical hacking & OSINT
- 🧩 DSA & problem solving
- 🚀 Startup/product building
- 🌐 Open-source projects

</td>

<td width="50%" valign="middle" align="center" bgcolor="#0a0d17">

### `DISCIPLINE TODAY`

# **FREEDOM TOMORROW**

<br>

`< / >`

**Let's build something amazing together.**

</td>
</tr>
</table>

<div align="center">

### ⭐ Thanks for visiting my profile!

</div>
'''

path = base / "README.md"
path.write_text(readme, encoding="utf-8")

print(f"Created: {path}")
print(f"Created: {base / 'banner.svg'}")
