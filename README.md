<div align="center">

<!-- Animated Header Wave -->
<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0A1A2B"/>
      <stop offset="100%" stop-color="#123C55"/>
    </linearGradient>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#2E86AB" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#2E86AB" stop-opacity="0"/>
    </radialGradient>
    <pattern id="ribbon" width="28" height="14" patternUnits="userSpaceOnUse">
      <path d="M0,7 L7,0 L14,7 L7,14 Z" fill="#D9A648" fill-opacity="0.55"/>
      <path d="M14,7 L21,0 L28,7 L21,14 Z" fill="none" stroke="#D9A648" stroke-opacity="0.35" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- background -->
  <rect width="1200" height="300" fill="url(#bgGrad)"/>
  <rect width="1200" height="300" fill="url(#glow)"/>

  <!-- top / bottom ribbon borders -->
  <rect x="0" y="0" width="1200" height="8" fill="url(#ribbon)"/>
  <rect x="0" y="292" width="1200" height="8" fill="url(#ribbon)"/>

  <!-- divider between emblem and text -->
  <line x1="330" y1="60" x2="330" y2="240" stroke="#1B4B6B" stroke-width="1.5"/>

  <!-- emblem: eight-point zellige star -->
  <g transform="translate(20,0)">
    <circle cx="150" cy="150" r="96" fill="none" stroke="#D9A648" stroke-opacity="0.4" stroke-width="1.5" stroke-dasharray="3 6">
      <animateTransform attributeName="transform" type="rotate" from="0 150 150" to="360 150 150" dur="90s" repeatCount="indefinite"/>
    </circle>
    <circle cx="150" cy="150" r="80" fill="#0A1A2B" fill-opacity="0.3" stroke="#1B4B6B" stroke-width="1"/>
    <polygon points="150.0,72.0 162.2,120.4 205.2,94.8 179.6,137.8 228.0,150.0 179.6,162.2 205.2,205.2 162.2,179.6 150.0,228.0 137.8,179.6 94.8,205.2 120.4,162.2 72.0,150.0 120.4,137.8 94.8,94.8 137.8,120.4"
      fill="#1B4B6B" fill-opacity="0.55" stroke="#D9A648" stroke-width="2" stroke-linejoin="round"/>
    <circle cx="150" cy="150" r="14" fill="#D9A648">
      <animate attributeName="fill-opacity" values="0.7;1;0.7" dur="4s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- text block -->
  <text x="384" y="132" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="52" font-weight="700" letter-spacing="2" fill="#F3E9D2">OTMANE HAMMADI</text>
  <text x="386" y="170" font-family="'Consolas', 'Courier New', monospace" font-size="21" fill="#D9A648">Full-Stack Developer · AI &amp; Data Science</text>

  <rect x="386" y="188" width="150" height="3" fill="#D9A648">
    <animate attributeName="width" values="150;210;150" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="fill-opacity" values="0.5;1;0.5" dur="5s" repeatCount="indefinite"/>
  </rect>

  <text x="386" y="222" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="16" fill="#8FA6B8">Fes, Morocco — building scalable, cloud-native applications</text>
</svg>

<br/>

<!-- Profile Views & Followers -->
<img src="https://komarev.com/ghpvc/?username=otm-ane0&amp;label=Profile+Views&amp;color=7C3AED&amp;style=flat-square" alt="profile views" />
&nbsp;
<a href="https://github.com/otm-ane0?tab=followers">
  <img src="https://img.shields.io/github/followers/otm-ane0?label=Followers&amp;style=flat-square&amp;color=7C3AED" />
</a>

</div>

---

## 🧑‍💻 About Me

```typescript
const otmane = {
  name: "Otmane Hammadi",
  location: "Fes, Morocco 🇲🇦",
  role: "Full-Stack Web Developer",
  education: [
    "Bachelor's — AI & Data Science @ Sup'Management (2025–2026)",
    "Associate's — Computer Science @ ISTA (2021–2023)"
  ],
  currentlyLearning: ["TypeScript", "Next.js", "Kubernetes", "DevOps"],
  passions: ["Scalable Apps", "Clean Architecture", "Cloud Technologies"],
  openTo: "Collaborations & New Opportunities 💬"
};
```

---

## 🎓 Education

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="https://img.shields.io/badge/SUP'MANAGEMENT-2025--2026-7C3AED?style=for-the-badge&amp;logo=graduation-cap&amp;logoColor=white"/>
      <br/><br/>
      🤖 <strong>Bachelor's Degree</strong><br/>
      <em>Artificial Intelligence &amp; Data Science</em>
    </td>
    <td align="center" width="50%">
      <img src="https://img.shields.io/badge/ISTA-2021--2023-4F46E5?style=for-the-badge&amp;logo=graduation-cap&amp;logoColor=white"/>
      <br/><br/>
      💻 <strong>Associate's Degree</strong><br/>
      <em>Computer Science</em>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

**Currently Learning**

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

</div>

---

## 📊 GitHub Stats


<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=otm-ane0&amp;show_icons=true&amp;theme=tokyonight&amp;include_all_commits=true&amp;count_private=true&amp;border_color=7C3AED&amp;bg_color=0d1117&amp;hide_border=false"/>
  &nbsp;
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=otm-ane0&amp;layout=compact&amp;langs_count=8&amp;theme=tokyonight&amp;border_color=7C3AED&amp;bg_color=0d1117"/>
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=otm-ane0&amp;theme=tokyonight&amp;border=7C3AED&amp;background=0d1117&amp;ring=A78BFA&amp;fire=A78BFA&amp;currStreakLabel=A78BFA&amp;stroke=7C3AED" alt="GitHub Streak" />
</div>

---

## 🚀 Featured Projects

<table align="center">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📦 Stock Management App</h3>
      <div align="center">
        <a href="#">
          <img src="https://img.shields.io/badge/Status-In%20Progress-orange?style=flat-square"/>
          &nbsp;
          <img src="https://img.shields.io/badge/Type-Web%20App-7C3AED?style=flat-square"/>
        </a>
      </div>
      <br/>
      <p>A comprehensive tool for managing construction material stock with real-time tracking and supplier management.</p>
      <ul>
        <li>📊 Real-time stock tracking (bricks, concrete, sand...)</li>
        <li>🔄 Full stock movement history</li>
        <li>📋 Purchase orders &amp; supplier management</li>
        <li>🚚 Delivery tracking &amp; delay handling</li>
      </ul>
      <div align="center">
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB"/>
        <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&amp;logo=node.js&amp;logoColor=white"/>
        <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&amp;logo=mongodb&amp;logoColor=white"/>
        <img src="https://img.shields.io/badge/Express-404D59?style=flat-square&amp;logo=express&amp;logoColor=white"/>
      </div>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🎉 Event Management App</h3>
      <div align="center">
        <a href="#">
          <img src="https://img.shields.io/badge/Status-In%20Progress-orange?style=flat-square"/>
          &nbsp;
          <img src="https://img.shields.io/badge/Type-Web%20App-7C3AED?style=flat-square"/>
        </a>
      </div>
      <br/>
      <p>An app to create, organize, and manage events end-to-end with category filtering and participant tracking.</p>
      <ul>
        <li>📅 Event creation with dates, times &amp; locations</li>
        <li>🏷️ Categories for smart search &amp; filtering</li>
        <li>👥 Registration &amp; participant management</li>
        <li>🔔 Notifications &amp; reminders</li>
      </ul>
      <div align="center">
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB"/>
        <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&amp;logo=node.js&amp;logoColor=white"/>
        <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&amp;logo=mongodb&amp;logoColor=white"/>
        <img src="https://img.shields.io/badge/Express-404D59?style=flat-square&amp;logo=express&amp;logoColor=white"/>
      </div>
    </td>
  </tr>
</table>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=otm-ane0&amp;bg_color=0d1117&amp;color=A78BFA&amp;line=7C3AED&amp;point=ffffff&amp;area=true&amp;hide_border=false&amp;border_color=7C3AED" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/otm-ane0/otm-ane0/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

---

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/otmane-hammadi-00b5ba356/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/the_goat_otmane/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/otm-ane0)

</div>

---

<!-- Footer Wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:24243e,50:302b63,100:0f0c29&amp;height=120&amp;section=footer&amp;animation=fadeIn" />

<div align="center">
  <em>⭐ Feel free to star my repos if you find them interesting!</em>
</div>
