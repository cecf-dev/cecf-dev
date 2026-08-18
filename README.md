<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Cristian%20Emanuel%20Ceron%20Franco&fontSize=38&fontColor=D8B4FE&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20%7C%20AI%2FAgent%20Engineering&descAlignY=55&descSize=18&descColor=A78BFA" width="100%"/>

<a href="https://github.com/cecf-dev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Computer+Engineering+Student+%40+UAM;Backend+%26+Data+Layer+Engineer;AI+%2F+Agentic+LLM+Integration;Building+Bot%C3%ADquin+Digital+Inteligente" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/GPA-4.0%20%2F%204.0-8B5CF6?style=for-the-badge&logo=googlescholar&logoColor=white"/>
<img src="https://img.shields.io/badge/UAM%20Azcapotzalco-Computer%20Engineering-6D28D9?style=for-the-badge&logo=academia&logoColor=white"/>
<img src="https://img.shields.io/badge/Location-Mexico%20City%2C%20MX-4C1D95?style=for-the-badge&logo=googlemaps&logoColor=white"/>

<br/><br/>

<a href="https://linkedin.com/in/cecf-dev"><img src="https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:cecf.contacto@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/cecf-dev"><img src="https://img.shields.io/badge/GitHub-8B5CF6?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=cecf-dev&label=Profile%20Views&color=8B5CF6&style=for-the-badge"/>
<img src="https://img.shields.io/github/followers/cecf-dev?label=Followers&style=for-the-badge&color=7C3AED&labelColor=1a1a2e"/>
<img src="https://img.shields.io/github/stars/cecf-dev?label=Stars&style=for-the-badge&color=6D28D9&labelColor=1a1a2e"/>

</div>

<br/>

## 🟣 About Me

<img align="right" width="260" src="https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg" />

I'm a **Computer Engineering student at UAM Azcapotzalco** (GPA 4.0, expected Jul. 2027) with hands-on experience across the full stack — from relational schema design to multimodal LLM integration. I co-built the backend and data layer for **Botiquín Digital Inteligente**, a three-tier medical application that uses vision-language models to digitize prescriptions and manage medication safety.

My focus sits at the intersection of **backend architecture**, **AI/agent-based systems**, and **product-minded engineering** — I care as much about response-time targets and test coverage as I do about the model pipeline behind a feature.

```txt
class Cristian:
    def __init__(self):
        self.role         = "Computer Engineering Student"
        self.focus        = ["Backend Architecture", "AI/Agent Integration", "Full-Stack Dev"]
        self.currently_at = "UAM Azcapotzalco — expected 2027"
        self.languages    = ["Spanish (native)", "English (B2)"]

    def open_to(self):
        return ["Software Engineering Internships", "Junior Full-Stack Roles", "AI/Agent Engineering"]
```

**🟪 Open To:** Professional internships and junior developer roles in full-stack development, backend engineering, or AI/agent-based applications.

<br/>

## 🟣 Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=py,java,cpp,c,js,html,css&theme=dark"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,tailwind,html,css&theme=dark"/>

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,express,mysql,firebase&theme=dark"/>

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=oracle,git,linux,vscode&theme=dark"/>

</div>

<br/>

## 🟣 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| **Multimodal LLM Integration** | 🟣🟣🟣🟣⚪ | Integrated Groq API (Llama 3 Vision) via `groq-sdk` to extract medication name, dosage, and expiration date from packaging photos |
| **RAG (Retrieval-Augmented Generation)** | 🟣🟣🟣⚪⚪ | Applied RAG concepts through Oracle Next Education / Alura AI & Cloud Developer track |
| **Agentic AI / Agentforce** | 🟣🟣🟣⚪⚪ | Certified Agentblazer Champion (Salesforce Agentforce) via Iberoamerican Technology Foundation |
| **Workflow Orchestration (n8n)** | 🟣🟣🟣⚪⚪ | Built automation flows as part of the OCI/LangChain/n8n certification track |
| **Applied AI Product Design** | 🟣🟣🟣🟣⚪ | Designed acceptance criteria (≥80% extraction accuracy) and validation UX for LLM-derived medical data |

</div>

<br/>

## 🟣 Featured Projects

<details open>
<summary><b>🩺 Botiquín Digital Inteligente (BDI) — Co-Developer</b></summary>
<br/>

Three-tier web application (Data / Logic / Presentation) for digitizing medical prescriptions and managing personal medicine cabinets using multimodal LLMs. Built collaboratively as an integration project at UAM Azcapotzalco.

| Attribute | Detail |
|---|---|
| **Stack** | React · Node.js · Express.js · MySQL · Groq API (Llama 3 Vision) · Google OAuth |
| **Scale** | Three-tier architecture with an isolated data-control (DC) module governing all DB access |
| **Performance** | Load-tested against a **99% availability** target and **<2s** response time for data retrieval |
| **Security** | Google OAuth login; frontend has no direct database access, mediated entirely through the DC layer |
| **Impact** | Targets **≥80%** accuracy on automated medication-label extraction and **≥95%** success on photo-capture functional tests |
| **Repository** | `github.com/cecf-dev` *(link project repo here)* |

**Engineering notes:** Designed the relational schema and data-control module, configured the Express backend and Groq/Llama 3 Vision integration for prescription and packaging OCR, built the expiration-validation algorithm, and integrated the official ICD-10 catalog for the medical history module. On the frontend, designed the React architecture and mockups, implemented the OAuth flow, the photo-capture component, and the dynamic form for validating LLM-extracted fields. Collaborated cross-functionally on handwritten-prescription interpretation, symptom-to-ICD-10 mapping, pharmacy geolocation (Leaflet/OpenStreetMap), and price comparison (SerpApi).

</details>

<details>
<summary><b>🗂️ Collaborative Kanban Board — Full-Stack Developer</b></summary>
<br/>

Real-time collaborative Kanban board with authentication and persistent state, built as an independent project.

| Attribute | Detail |
|---|---|
| **Stack** | React · Firebase Auth · Firestore |
| **Scale** | Multi-user, real-time synchronized board state |
| **Performance** | Real-time updates via Firestore listeners |
| **Security** | Firebase Authentication-gated access per user/board |
| **Impact** | End-to-end ownership: auth, data modeling, and UI |
| **Repository** | `github.com/cecf-dev` *(link project repo here)* |

**Engineering notes:** Implemented user authentication and real-time data persistence end-to-end with Firebase Auth and Firestore, focused on low-latency state sync across concurrent users.

</details>

<br/>

## 🟣 Experience

**Member, Electronics Department — UAMOTORS (Formula SAE Multidisciplinary Team)**
`Apr. 2025 – Present`

Contributing to a student engineering team transitioning into a structured, multidisciplinary Formula SAE program.

- Collaborate on power distribution design and integration
- Work on motor control interfaces
- Implement sensor systems and driver-side data acquisition/instrumentation

`Embedded Systems` `Sensors` `Data Acquisition` `Team Engineering`

<br/>

## 🟣 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏅 **Perfect Academic Standing** | GPA 4.0 / 4.0 at UAM Azcapotzalco, Computer Engineering |
| 🏅 **Agentblazer Champion** | Recognized under the Iberoamerican Technology Foundation's AI & Agentforce track |
| 🏅 **AI & Cloud Developer Track Completion** | Oracle Next Education (ONE) & Alura — OCI, LangChain, n8n, RAG |

</div>

<br/>

## 🟣 Certifications

**Iberoamerican Technology Foundation (ITF)**

<img src="https://img.shields.io/badge/Agentblazer%20Champion-AI%20%26%20Agentforce%20Trainee-6D28D9?style=for-the-badge&logo=salesforce&logoColor=white"/>

**Oracle Next Education (ONE) & Alura**

<img src="https://img.shields.io/badge/OCI%20%7C%20LangChain%20%7C%20n8n%20%7C%20RAG-AI%20%26%20Cloud%20Developer-8B5CF6?style=for-the-badge&logo=oracle&logoColor=white"/>

<br/><br/>

## 🟣 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=cecf-dev&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=A78BFA&icon_color=8B5CF6&text_color=c9d1d9&count_private=true" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=cecf-dev&theme=tokyonight&hide_border=true&background=0d1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cecf-dev&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=A78BFA&text_color=c9d1d9&langs_count=10" width="49%"/>

</div>

<br/>

## 🟣 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=cecf-dev&theme=algolia&no-frame=true&no-bg=true&margin-w=8&column=7"/>

</div>

<br/>

## 🟣 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=cecf-dev&theme=react-dark&hide_border=true&bg_color=0d1117&color=A78BFA&line=8B5CF6&point=D8B4FE"/>

</div>

<br/>

## 🟣 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/cecf-dev/cecf-dev/output/github-contribution-grid-snake-dark.svg"/>

</div>

> *Generate this via the [platane/snk](https://github.com/Platane/snk) GitHub Action on your profile repo to activate.*

<br/>

## 🟣 Current Focus

```yaml
current_focus:
  learning:
    - Analysis and Design of Algorithms
    - Advanced RAG architectures
    - Agentic system design (Agentforce, LangChain)
  building:
    - Botiquín Digital Inteligente (BDI)
    - Personal open-source tooling
  exploring:
    - Multimodal LLM applications in healthcare
    - Motorsport data acquisition (UAMOTORS)
  open_to:
    - Software Engineering Internships
    - Junior Full-Stack / AI Engineering Roles
```

<br/>

## 🟣 Connect

<div align="center">

<a href="mailto:cecf.contacto@gmail.com"><img src="https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/cecf-dev"><img src="https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/cecf-dev"><img src="https://img.shields.io/badge/GitHub-8B5CF6?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

<div align="center">

*"Build things that matter, measure them honestly, and ship."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

</div>
