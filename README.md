<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6DB33F,50:1572B6,100:61DAFB&height=200&section=header&text=Hemraj%20Kalathoki&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Engineer%20%E2%80%A2%20Java%20%2B%20Spring%20Boot%20%2B%20React&descAlignY=55&descSize=18" width="100%" alt="Hemraj Kalathoki" />

<a href="https://profile.hemrajkalathoki.com.np/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=6DB33F&center=true&vCenter=true&width=760&lines=Backend-Focused+Full+Stack+Developer+%F0%9F%87%B3%F0%9F%87%B5;2.5%2B+years+shipping+production+Java+systems;Spring+Boot+%7C+React+%7C+PostgreSQL+%7C+Docker+%7C+AWS;I+ship+real+products%2C+not+just+demos" alt="What I do" />
</a>

<br/>

<a href="https://profile.hemrajkalathoki.com.np/"><img src="https://img.shields.io/badge/Portfolio-Live-6DB33F?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1117" alt="Portfolio" /></a>
<a href="https://linkedin.com/in/hemrajkalathoki"><img src="https://img.shields.io/badge/Open_to-Full--Stack_Roles-1572B6?style=for-the-badge&labelColor=0d1117" alt="Open to work" /></a>
<a href="https://github.com/HemrajKalathoki?tab=followers"><img src="https://img.shields.io/github/followers/HemrajKalathoki?label=Followers&style=for-the-badge&color=61DAFB&labelColor=0d1117" alt="Followers" /></a>
<img src="https://komarev.com/ghpvc/?username=HemrajKalathoki&label=Profile+Views&style=for-the-badge&color=6DB33F" alt="Profile views" />

</div>

---

## 👨‍💻 About Me

I'm a **backend-focused Full Stack Developer** from Kathmandu with **2.5+ years of production experience** building and shipping Java / Spring Boot systems end to end.

Right now I own backend development for **BookStreet** at Autaway — a live digital book marketplace where I've shipped a full **PayPal payments integration**, **Auth0** identity and access control, and **30+ REST APIs**. On my own time I built **[Arthova](https://arthova.app)** single-handedly: 19 feature modules, live in production on AWS.

I enjoy the unglamorous parts — schema design, auth flows, transaction boundaries, and the code that still has to be correct at 3 a.m.

```java
public class Hemraj {

    String   role       = "Full Stack Software Developer @ Autaway";
    String   location   = "Kathmandu, Nepal 🇳🇵";
    String   experience = "2.5+ years in production";

    String[] coreStack  = { "Java", "Spring Boot", "React", "TypeScript",
                            "PostgreSQL", "Redis", "Docker", "AWS" };

    String   shipped    = "PayPal payments · Auth0 IAM · 30+ REST APIs";
    String   building   = "Arthova — finance + community platform (solo, live)";
    String   grinding   = "700+ LeetCode problems in Java";

    String   principle  = "Make it correct, then make it fast, then make it pretty.";
    boolean  coffee     = true; // always
}
```

<table>
<tr>
<td>🔭</td><td><b>Working on</b></td><td><b>BookStreet</b> @ Autaway — payments, identity & admin APIs on a live marketplace</td>
</tr>
<tr>
<td>🚀</td><td><b>Building solo</b></td><td><a href="https://arthova.app">Arthova</a> — 19-module finance + community platform, live on AWS</td>
</tr>
<tr>
<td>💬</td><td><b>Ask me about</b></td><td>Spring Boot architecture, REST API design, payment integrations, PostgreSQL</td>
</tr>
<tr>
<td>🧠</td><td><b>Algorithms</b></td><td>700+ LeetCode problems solved in Java · 🥇 1st place, LearnYard HackerRank contest</td>
</tr>
<tr>
<td>🤝</td><td><b>Open to</b></td><td>Full-Stack / Backend Engineer roles — Kathmandu or remote</td>
</tr>
<tr>
<td>⚡</td><td><b>Fun fact</b></td><td>I code with music on and coffee within arm's reach ☕</td>
</tr>
</table>

---

# 🌟 Featured Work

## 💰 Arthova — Personal Finance + Community Platform

<div align="center">
<a href="https://arthova.app"><img src="https://img.shields.io/badge/🌐_Live-arthova.app-6DB33F?style=for-the-badge&labelColor=0d1117" alt="Live app" /></a>
<img src="https://img.shields.io/badge/Status-Active_Development-1572B6?style=for-the-badge&labelColor=0d1117" alt="Status" />
<img src="https://img.shields.io/badge/Scale-Production_Grade-FF9900?style=for-the-badge&labelColor=0d1117" alt="Scale" />
</div>

> **Architected, built and deployed single-handedly.** 19 feature-sliced modules covering multi-account banking, income / expense / budget / goal tracking, analytics, a **real-time social + messaging layer**, and a full admin back office — built to production standards, not prototype standards.

| Layer | Details |
|---|---|
| **Backend** | Spring Boot 3.5 · Java 21 · PostgreSQL · Redis · Flyway migrations · MapStruct |
| **Frontend** | React 18 · TypeScript · Vite · TanStack Query · Zustand · Tailwind CSS · shadcn/ui |
| **Real-time** | WebSocket over STOMP / SockJS — 1:1 & group chat, live notifications |
| **Security** | JWT access/refresh in `HttpOnly` cookies · `SameSite` CSRF defence · role-gated portals · rate limiting |
| **Infra** | Docker + docker-compose → GitHub Actions CI/CD → **AWS EC2** behind **Nginx** with SSL |
| **Design** | Feature-sliced vertical architecture · service-layer transaction boundaries · migration-owned schema |

**Engineering highlights**

- 🔐 Cookie-based auth with refresh rotation across three role-gated portals (`USER` / `SUB_ADMIN` / `SUPER_ADMIN`)
- ⚡ Page-scoped aggregation endpoints that eliminate N+1 queries and payload over-fetching
- 🔌 Realtime connection lifecycle handled properly — reconnection, subscription management, delivery guarantees
- 📴 Offline-capable, idempotent sync protocol designed to be shared with a future native mobile client
- 🚢 Zero-touch deploys — every push to `main` builds, tests, ships and rolls over the running container

<br/>

## 🧑‍💼 Developer Portfolio — Full-Stack, Database-Driven

<div align="center">
<a href="https://profile.hemrajkalathoki.com.np/"><img src="https://img.shields.io/badge/🌐_Live-profile.hemrajkalathoki.com.np-1572B6?style=for-the-badge&labelColor=0d1117" alt="Live site" /></a>
<img src="https://img.shields.io/badge/Type-Full--Stack_SPA-6DB33F?style=for-the-badge&labelColor=0d1117" alt="Type" />
</div>

> Not a static template — a **self-managed full-stack application**. Spring Boot REST APIs serve projects, blogs and certificates through a **secure admin dashboard**, so I update my own portfolio from a UI instead of editing markup and redeploying.

| Layer | Details |
|---|---|
| **Frontend** | React · Tailwind CSS · responsive, component-driven UI |
| **Backend** | Java · Spring Boot · REST APIs · layered service architecture |
| **Database** | MySQL · normalised schema · JPA / Hibernate |
| **Security** | JWT authentication with role-based access control (RBAC) |
| **Deployment** | Custom domain, live in production |

**Why it's built this way**

- 🔐 **Secure admin dashboard** — JWT auth with RBAC guarding every content-management endpoint
- 🗄️ **Content is data, not markup** — projects, blogs and certificates live in MySQL over a normalised schema
- 📬 **Dual-channel contact form** — submissions persist to MySQL *and* dispatch email via Web3Forms, so nothing is lost if either path fails
- 🧱 **Proper layering** — controller → service → repository, the same structure I use on production work

<div align="center">
<a href="https://profile.hemrajkalathoki.com.np/"><b>→ Visit the live site</b></a>
</div>

---

## 📦 More Projects

<div align="center">

<a href="https://github.com/HemrajKalathoki/company-incorporation-tool"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=HemrajKalathoki&repo=company-incorporation-tool&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6DB33F&icon_color=61DAFB" alt="Company Incorporation Tool" /></a>
<a href="https://github.com/HemrajKalathoki/BazaarHub"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=HemrajKalathoki&repo=BazaarHub&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6DB33F&icon_color=61DAFB" alt="BazaarHub" /></a>

<a href="https://github.com/HemrajKalathoki/HRFoodHouse"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=HemrajKalathoki&repo=HRFoodHouse&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6DB33F&icon_color=61DAFB" alt="HRFoodHouse" /></a>
<a href="https://github.com/HemrajKalathoki/CODING-SAMURAI-INTERNSHIP-TASK"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=HemrajKalathoki&repo=CODING-SAMURAI-INTERNSHIP-TASK&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6DB33F&icon_color=61DAFB" alt="Coding Samurai Internship" /></a>

</div>

| Project | What it is | Stack |
|---|---|---|
| **[Company Incorporation Tool](https://github.com/HemrajKalathoki/company-incorporation-tool)** | Guided workflow tool for company registration paperwork | ![TS](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **[BazaarHub](https://github.com/HemrajKalathoki/BazaarHub)** | E-commerce backend — catalog, cart, orders, auth on Spring Boot MVC | ![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **[HRFoodHouse](https://github.com/HemrajKalathoki/HRFoodHouse)** | Restaurant ordering system (BCA 4th semester project) | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **[Coding Samurai Internship](https://github.com/HemrajKalathoki/CODING-SAMURAI-INTERNSHIP-TASK)** | Java internship task solutions | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **[WeatherApp](https://github.com/HemrajKalathoki/WeatherApp)** | Live weather lookup against a public API | ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **[React Learning](https://github.com/HemrajKalathoki/ReactLearningWithRevision)** | Hooks, state and patterns, practised properly | ![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB) |

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

### ⚙️ Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

</td>
<td valign="top" width="50%">

### 🎨 Frontend

![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

</td>
</tr>
<tr>
<td valign="top">

### 🗄️ Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

</td>
<td valign="top">

### 🚀 DevOps & Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=HemrajKalathoki&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6DB33F&icon_color=61DAFB&include_all_commits=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HemrajKalathoki&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6DB33F&langs_count=8" alt="Top languages" />

<br/><br/>

<img width="98%" src="https://streak-stats.demolab.com?user=HemrajKalathoki&theme=tokyonight&hide_border=true&background=0d1117&ring=6DB33F&fire=61DAFB&currStreakLabel=6DB33F" alt="GitHub streak" />

<br/><br/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=HemrajKalathoki&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=6DB33F&line=61DAFB&point=ffffff&area=true&area_color=1572B6" alt="Contribution activity graph" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=HemrajKalathoki&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="Trophies" />

</div>

---

## 💼 Where I've Worked

| Role | Company | When | What I shipped |
|---|---|---|---|
| **Full Stack Software Developer** | Autaway Pvt. Ltd. | Apr 2026 – Present | PayPal payments, Auth0 IAM, 30+ REST APIs and a transactional email pipeline for **BookStreet**, a live book marketplace |
| **Software Developer** | Artova Solutions Pvt. Ltd. | Sep 2024 – Feb 2026 | Spring Boot backend services and REST APIs, MySQL query optimisation, API contract design with frontend and QA |
| **Software Developer Intern** | Artova Solutions Pvt. Ltd. | Jun 2024 – Aug 2024 | Backend modules in Spring Boot and MySQL, full SDLC within an agile team |

🎓 **BCA**, Ambikeshwori Campus, Dang — CGPA **3.53 / 4.0**

---

## 🧩 Problem Solving

<div align="center">

<b>700+ problems solved in Java</b> · 🥇 <b>1st place</b> — HackerRank contest organised by LearnYard

<br/><br/>

<a href="https://leetcode.com/u/Hemraj-Kalathoki/"><img src="https://img.shields.io/badge/LeetCode-700%2B_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
<a href="https://www.geeksforgeeks.org/user/hemraj_kalathoki/"><img src="https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="GeeksforGeeks" /></a>
<a href="https://stackoverflow.com/users/25585611"><img src="https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="Stack Overflow" /></a>

</div>

---

## 🤝 Let's Work Together

<div align="center">

I'm open to **Full-Stack / Backend Engineer** roles and interesting collaborations.<br/>
The fastest way to reach me is email — I reply to all of them.

<br/>

<a href="mailto:hemraj.kalathoki3@gmail.com"><img src="https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://linkedin.com/in/hemrajkalathoki"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://profile.hemrajkalathoki.com.np/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>

<br/>

<a href="https://x.com/HR_Kalathoki"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<a href="https://instagram.com/kalathoki.hemraj"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
<a href="https://www.facebook.com/kalathoki.hemraj/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" /></a>

</div>

<div align="center">

<br/>

***"Stay curious, keep building, and never stop learning."***

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:61DAFB,50:1572B6,100:6DB33F&height=120&section=footer" width="100%" alt="" />

</div>
