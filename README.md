<div align="center">

# Hey, I'm Aditya 👋

**Backend Engineer · IIIT Kottayam '27 · Building systems that don't break in production**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aditya-bhimanwar)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/adityabhimanwar123)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:adityabhimanwar123@gmail.com)

</div>

---

## 👨‍💻 About Me

I'm a backend-focused engineer who cares about **correctness over cleverness** — atomic operations, timing-safe comparisons, zero-downtime migrations, resilient queues. Not just "it works."

- 🎓 **B.Tech ECE @ IIIT Kottayam** (2023–2027) | CGPA: **8.65 / 10**
- 💼 **Ex-SWE Intern @ Granville Tech** — sole backend intern on a live EdTech platform, shipped **30+ REST APIs** across 6 domains directly to production under CTO review
- 🧠 **328+ LeetCode problems** | Contest Rating: **1641** | Top 15% globally
- 🎯 Actively targeting **backend / SDE internships** at product companies & startups

---

## 🛠 Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?style=flat-square&logo=express&logoColor=%2361DAFB)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=JSON%20web%20tokens)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)

**Databases & Cloud**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

**Testing & Tools**

![Jest](https://img.shields.io/badge/Jest-%23C21325?style=flat-square&logo=jest&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078d7.svg?style=flat-square&logo=visual-studio-code&logoColor=white)

---

## 🚀 Featured Projects

### 🔐 [VaultShare](https://github.com/developer7620/vaultshare) — Secure File Sharing Platform

A production-grade file sharing system built with security and concurrency correctness as first-class concerns.

| Decision | Why It Matters |
|----------|----------------|
| HMAC-SHA256 signed uploads direct to Cloudinary | Zero memory pressure & DoS surface on backend |
| MongoDB atomic `findOneAndUpdate` with `$inc` | Race condition–proof download limits (same pattern as ticket-sale systems) |
| Dummy hash bcrypt comparison (~250ms always) | Eliminates timing side-channel — attackers can't infer file state |
| `CloudinaryProvider` / `S3Provider` abstraction | Zero-downtime storage migration via single env change |
| Dead-letter queue + exponential backoff (cap: 60min) | Resilient failed deletion handling |
| 47-test Jest suite with concurrency regression test | Asserts exactly 3/10 simultaneous requests succeed on a limit-3 file |

`Node.js` `Express.js` `MongoDB` `Cloudinary` `bcrypt` `Jest` `React.js` `node-cron`

---

### 🎙 [AI Virtual Assistant](https://github.com/developer7620/AI_VIRTUAL_ASSISTANT) — Voice-Based Full Stack Web App

Full-stack voice assistant supporting **15+ commands** with real-time speech recognition and synthesis.

- 🎤 Web Speech API for STT/TTS — real interaction, not a demo
- 🔐 JWT-based auth with protected routes and stateless session management
- ⚛️ Global state via React Context API; all command routing on the backend

`React.js` `Node.js` `Express.js` `Tailwind CSS` `Web Speech API` `JWT`


---

## 🏆 Achievements

- 🥇 **Top 15% globally** on LeetCode — 328+ problems solved, Contest Rating 1641
- 🚀 **Sole backend intern** at Granville Tech — 30+ production API endpoints shipped under CTO review
- 📐 **JEE Mains qualified** — top 3% out of 1.2M+ candidates (Rank ~38,000)

---

<div align="center">

*"Make it work. Make it right. Make it fast — in that order."*

</div>
