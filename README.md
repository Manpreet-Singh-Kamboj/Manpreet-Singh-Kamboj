<a name="top"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg" />
  <img src="assets/header-light.svg" alt="Manpreet Singh. Software engineer building backends, data pipelines and the apps on top." width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/marquee-dark.svg" />
  <img src="assets/marquee-light.svg" alt="Java, Spring Boot, Node.js, TypeScript, React, Python, PySpark, Microsoft Fabric, AWS, GCP, PostgreSQL, Docker" width="600" />
</picture>

<br/>

<a href="https://msinghdev.vercel.app">Portfolio</a> &nbsp;·&nbsp;
<a href="https://linkedin.com/in/manpreet-swe">LinkedIn</a> &nbsp;·&nbsp;
<a href="mailto:manpreet.swe@outlook.com">Email</a> &nbsp;·&nbsp;
<a href="https://www.leetcode.com/manpreetsingh2003">LeetCode</a>

<br/><br/>

<sub>
<a href="#about">About</a> &nbsp;·&nbsp;
<a href="#experience">Experience</a> &nbsp;·&nbsp;
<a href="#projects">Projects</a> &nbsp;·&nbsp;
<a href="#skills">Skills</a> &nbsp;·&nbsp;
<a href="#activity">Activity</a> &nbsp;·&nbsp;
<a href="#contact">Contact</a>
</sub>

</div>

<br/>

<a name="about"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/about-dark.svg" />
  <img src="assets/about-light.svg" alt="Backend first. Full stack too." width="100%" />
</picture>

Master of Applied Computing candidate at Wilfrid Laurier University.<br/>
1.5+ years of co-op and internship work across Java and Node.js backends,<br/>
React, Vue and Svelte front ends, and cloud data pipelines.

Recently: PySpark pipelines processing 250K+ daily transactions from 1,100+ stores,<br/>
and Spring Boot APIs serving geo-targeted content to 100K+ sales reps.

<table>
  <tr>
    <td align="center"><sub>NOW</sub><br/><b>Home Hardware</b><br/>IT eCommerce Co-op</td>
    <td align="center"><sub>STUDYING</sub><br/><b>Wilfrid Laurier</b><br/>M.A.C., Apr 2027, GPA 11.34/12</td>
  </tr>
  <tr>
    <td align="center"><sub>CERTIFIED</sub><br/><b>AWS</b><br/>Cloud Practitioner</td>
    <td align="center"><sub>AVAILABLE</sub><br/><b>Roles from 2027</b><br/>Waterloo, ON</td>
  </tr>
</table>

</div>

<br/>

<a name="experience"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/experience-dark.svg" />
  <img src="assets/experience-light.svg" alt="Production code, real teams." width="100%" />
</picture>

</div>

<details open>
<summary><b>Home Hardware</b> &nbsp;·&nbsp; IT eCommerce Co-op, Full Stack &nbsp;·&nbsp; <sub>May – Dec 2026</sub></summary>
<br/>

- Shipped 10+ user stories in 1.5 months for a new Pro Dashboard, with reusable Vue.js and Svelte components for data tables and filtering
- Built PySpark ETL pipelines on Microsoft Fabric (Azure) that ingest 250K+ daily POS transactions from 1,100+ stores
- Designed a cross-cloud sync from a Fabric Delta Table to Cloud SQL, incremental by timestamp, through a serverless GCP Cloud Function
- Documented the legacy Reassignment Shipments codebase for future work and production troubleshooting

</details>

<details>
<summary><b>Wilfrid Laurier University</b> &nbsp;·&nbsp; Instructional Assistant, System Programming &nbsp;·&nbsp; <sub>Jan – Apr 2026</sub></summary>
<br/>

- Mentored 50+ students in Shell scripting and C, reviewing labs for code quality, memory management and readability

</details>

<details>
<summary><b>CoreAI Technologies</b> &nbsp;·&nbsp; Full-Stack Software Developer &nbsp;·&nbsp; <sub>May – Oct 2025</sub></summary>
<br/>

- Built and component-tested a health analytics dashboard with Next.js, React and TanStack Query
- Created a categorization system for 400+ biomarkers that simplified backend retrieval and frontend navigation

</details>

<details>
<summary><b>SalesCode.ai</b> &nbsp;·&nbsp; Software Engineer Intern &nbsp;·&nbsp; <sub>Jun – Dec 2024</sub></summary>
<br/>

- Built Spring Boot REST APIs on auto-scaling AWS EC2 and S3 serving geo-targeted banners to 100K+ sales reps, with a 15% lift in click-through rate
- Cut the Flutter client's memory use by over 30% (89MB to 62MB) with widget refactoring and lazy loading

</details>

<p align="right"><sub><a href="#top">Back to top ↑</a></sub></p>

<a name="projects"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/projects-dark.svg" />
  <img src="assets/projects-light.svg" alt="Side projects, taken seriously." width="100%" />
</picture>

</div>

### [PulseWatch](https://github.com/Manpreet-Singh-Kamboj/PulseWatch)
<sub>2nd runner-up, Startup Build Hackathon 2026 · backend built in 48 hours</sub>

Uptime monitoring with AI-written incident summaries.

- Cron-scheduled website, API and SSL checks that classify targets as UP, DOWN or DEGRADED and track each incident from outage to recovery
- OpenAI incident summaries and a streaming dashboard chat assistant, with live check events pushed over Server-Sent Events
- JWT cookie sessions, role-based access, email OTP and Google Sign-In, with alerts by email, Twilio SMS, Slack and Discord

<img src="https://skillicons.dev/icons?i=react,ts,nodejs,express,mongodb,redis,docker&perline=7" height="40" alt="React, TypeScript, Node.js, Express, MongoDB, Redis, Docker" />

<details>
<summary>How it works</summary>
<br/>

```mermaid
flowchart LR
    A["Cron scheduler"] --> B["Website, API and SSL checks"]
    B --> C{"Status"}
    C --> D[("MongoDB")]
    C -->|"DOWN"| E["OpenAI incident summary"]
    C --> F["Alerts: email, SMS, Slack, Discord"]
    D --> G["Server-Sent Events"]
    G --> H["React dashboard"]
```

</details>

### [Qure](https://github.com/Manpreet-Singh-Kamboj/Qure)
<sub>React Native app and Node.js backend</sub>

Real-time queue and token management for clinics.

- Socket.IO rooms push live queue updates to patients and staff, behind JWT authentication and role-based authorization
- Atomic PostgreSQL transactions keep token assignment consistent
- BullMQ and Redis handle background uploads, cutting image upload latency from about 13s to under 500ms

<img src="https://skillicons.dev/icons?i=nodejs,ts,react,postgres,redis,docker&perline=6" height="40" alt="Node.js, TypeScript, React Native, PostgreSQL, Redis, Docker" />

<details>
<summary>How it works</summary>
<br/>

```mermaid
flowchart LR
    A["React Native app"] <-->|"Socket.IO"| B["Node.js and Express API"]
    B --> C[("PostgreSQL")]
    B --> D["BullMQ and Redis queue"]
    D --> E["Background upload worker"]
```

</details>

### [Skin Lesion Classification](https://github.com/Manpreet-Singh-Kamboj)
<sub>Python, EfficientNet-B4, Grad-CAM++</sub>

Multi-task model for skin lesion diagnosis and melanoma detection on the imbalanced HAM10000 dataset.

- Focal loss and weighted sampling reached 0.753 melanoma recall and 0.928 AUC-ROC
- Deep-ensemble uncertainty estimates and Grad-CAM++ explanations, served through a Flask REST API to a React (Vite) frontend

<img src="https://skillicons.dev/icons?i=python,pytorch,flask,react,vite&perline=5" height="40" alt="Python, PyTorch, Flask, React, Vite" />

<p align="right"><sub><a href="#top">Back to top ↑</a></sub></p>

<a name="skills"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/skills-dark.svg" />
  <img src="assets/skills-light.svg" alt="The tools I reach for." width="100%" />
</picture>

<sub>LANGUAGES</sub><br/>
<img src="https://skillicons.dev/icons?i=java,python,ts,js,c,bash&perline=6" alt="Java, Python, TypeScript, JavaScript, C, Bash" />

<sub>WEB AND APIS</sub><br/>
<img src="https://skillicons.dev/icons?i=spring,react,nextjs,nodejs,express,flask&perline=6" alt="Spring Boot, React, Next.js, Node.js, Express, Flask" />

<sub>CLOUD AND DATA</sub><br/>
<img src="https://skillicons.dev/icons?i=aws,gcp,azure,spark,postgres,mongodb&perline=6" alt="AWS, GCP, Azure, Spark, PostgreSQL, MongoDB" />

<sub>TOOLS</sub><br/>
<img src="https://skillicons.dev/icons?i=redis,docker,git,postman,jest,vitest&perline=6" alt="Redis, Docker, Git, Postman, Jest, Vitest" />

</div>

<details>
<summary>Everything else I've worked with</summary>
<br/>

SQL, Bash/Zsh, Vue.js, Svelte, Redux, TanStack Query, Socket.IO, REST APIs, Microsoft Fabric, Azure DevOps, JUnit, Supertest

</details>

<p align="right"><sub><a href="#top">Back to top ↑</a></sub></p>

<a name="activity"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/activity-dark.svg" />
  <img src="assets/activity-light.svg" alt="GitHub and LeetCode." width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Manpreet-Singh-Kamboj/Manpreet-Singh-Kamboj/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Manpreet-Singh-Kamboj/Manpreet-Singh-Kamboj/output/github-snake.svg" alt="GitHub contribution graph" width="100%" />
</picture>

<br/><br/>

<a href="https://www.leetcode.com/manpreetsingh2003">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://leetcard.jacoblin.cool/manpreetsingh2003?ext=heatmap&border=0&radius=14&theme=dark" />
  <img src="https://leetcard.jacoblin.cool/Manpreet_03?ext=heatmap&border=0&radius=14&theme=light" alt="LeetCode stats and activity heatmap" width="520" />
</picture>
</a>

</div>

<p align="right"><sub><a href="#top">Back to top ↑</a></sub></p>

<a name="contact"></a>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/contact-dark.svg" />
  <img src="assets/contact-light.svg" alt="Let's talk. Backend, full-stack and data roles starting 2027." width="100%" />
</picture>

<a href="mailto:manpreet.swe@outlook.com">manpreet.swe@outlook.com</a>

<a href="https://linkedin.com/in/manpreet-swe">LinkedIn</a> &nbsp;·&nbsp;
<a href="https://msinghdev.vercel.app">Portfolio</a> &nbsp;·&nbsp;
<a href="https://github.com/Manpreet-Singh-Kamboj">GitHub</a> &nbsp;·&nbsp;
<a href="https://www.leetcode.com/Manpreet_03">LeetCode</a>

</div>
