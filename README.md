<div align="center">

# Leeland Raj Kumar

### Systems Architecture Engineer &nbsp;·&nbsp; Full-Stack Developer

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&pause=1000&color=2DD4BF&center=true&vCenter=true&width=620&height=45&lines=Systems+Architecture+Engineer;I+build+internal+platforms+teams+actually+use;I+get+the+structure+right+before+the+code;Full-stack,+schema+to+UI" alt="typing intro" />

📍 Johor Bahru, Malaysia &nbsp;·&nbsp; Open to roles in Malaysia and remote / international

<a href="mailto:leelandrajkumar98@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/leelandrk"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://leeland.site"><img src="https://img.shields.io/badge/Portfolio-2DD4BF?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>

</div>

---

I build internal platforms from scratch. Usually that means turning a mess of manual processes into one system a team actually relies on. I try to get the structure right before writing much code, since that's what holds up once people start using it. Right now I'm doing that end to end: database schema, access control, real-time data, and the frontend on top.

## Featured work

### NEXA: Internal Operations & Architecture Platform
I took this from an empty repo to company-wide use in under a year, mostly on my own. It pulls identity, access, ticketing, and operational data into one interface, with permissions handled by a custom IAM layer that everything routes through. The backend checks access on its own instead of trusting the UI. On top of that it runs real-time data, 3D hardware views built with Three.js, analytics dashboards, and exports to PDF, Excel, and PowerPoint.
**Stack** · TypeScript, React 18, Node/Express, PostgreSQL, Socket.IO, Three.js
*Internal project, so I'm keeping it high level with no repo link.*

### DHViewer + Codex: Real-time TTRPG platform with an AI co-pilot
A live companion app for Daggerheart tabletop sessions. Party and combat state (HP, conditions, fear, 3D dice) stays in sync across everyone's screens over Socket.IO. It's paired with Codex, a Claude-powered notes assistant with Ask, Story, Plan, and Language modes plus two-way Obsidian sync. This is the project where I've done the most real LLM integration.
**Stack** · React 19, Vite, Material UI, Zustand, Node/Express, Socket.IO, Anthropic SDK
*Code private, opening up soon.*

### AFKlog: Human-centered social-accountability PWA
An installable PWA for keeping a small group loosely in touch. People post hourly check-ins (photo, text, or short video), work through 51 achievements, get push reminders, and every night an FFmpeg job stitches everyone's day into a split-screen recap. I built it around how people actually behave rather than an ideal user, so it has quiet hours, low-battery days, and a nudge for when you get stuck. The inclusive-design side of it was on purpose.
**Stack** · React, Express, SQLite, Web Push, FFmpeg, PWA
*Code private, opening up soon.*

### Kaethis: A constructed language and its AI translator
A language I built from scratch. It has a full phonology, three separate writing systems, and a grammar with evidentiality, meaning the grammar itself marks how you know what you're saying. It plugs into Codex's Language mode, which translates it and locks in new words as they get coined during a session.
**Focus** · Language design, NLP, LLM integration
*Living reference, no repo.*

### Hero Brain: Production site for an education service
A live site for a Johor education service that helps kids with literacy, maths, and social-emotional learning. React, TypeScript, and Tailwind on the front, with a git-based CMS and email handling behind it.
**Stack** · React, TypeScript, Tailwind CSS, Nodemailer
Live: [herobrain.space](https://herobrain.space)

### MIPS Emulator: A MIPS CPU emulator in C++
A MIPS processor emulator I wrote in C++ during my degree. It decodes and runs the instructions itself. It's the low-level side of my work, and a change of pace from the platform stuff.
**Stack** · C++
Repo: [github.com/iridescented/MIPS_Emulator](https://github.com/iridescented/MIPS_Emulator)

**Also:** *Transaction Tracker*, which takes transactions people enter in Discord, stores them, and shows them on a web dashboard with charts and a searchable view. `Node.js · Discord.js · Wise API · TypeScript`

## Tech

|              |                                                                                             |
| ------------ | ------------------------------------------------------------------------------------------- |
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Material UI](https://img.shields.io/badge/Material%20UI-007FFF?style=flat-square&logo=mui&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) |
| **Backend**  | ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white) |
| **Data**     | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Tooling**  | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![Anthropic SDK](https://img.shields.io/badge/Anthropic%20SDK-191919?style=flat-square&logo=anthropic&logoColor=white) |

## Certifications

**Meta Back-End Developer Professional Certificate** (Coursera)
