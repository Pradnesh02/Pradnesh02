<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=shark&color=1E1E2E&fontColor=CBA6F7&text=%3E_%20PRADNESH%20KHASNIS&fontSize=38&desc=AI-Focused%20Software%20Engineer%20%E2%80%94%20Final%20Year%20CSE&descColor=A6E3A1&animation=fadeIn&fontAlignY=35&descAlignY=55" />
  <br />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=800&color=CBA6F7&center=true&vCenter=true&width=820&lines=%24+whoami+%E2%86%92+CSE+Student+%7C+AI+Engineering;%24+skills+%E2%86%92+Python+%7C+FastAPI+%7C+Flask+%7C+React;%24+cat+building.txt+%E2%86%92+RAG+%2B+LLM+Eval+Systems;%24+status+%E2%86%92+Open+to+Internships+%2F+New+Grad+Roles" />
  <br /><br />

  <a href="https://github.com/Pradnesh02"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pradnesh-khasnis-a146a9358/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pradneshkhasnis02@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://rti-sahayak-smoky.vercel.app/"><img src="https://img.shields.io/badge/Live-RTI%20Sahayak-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</div>

<br />

> **whoami**

Final-year Computer Science & Engineering student focused on AI engineering — I build and deploy production-style systems, not just tutorials. My recent work centers on retrieval-augmented LLM apps and evaluation infrastructure: systems that don't just generate outputs, but verify, score, and catch their own regressions before they ship.

```bash
$ cat .profile

ROLE      =  B.Tech CSE (Final Year) — AI Engineering Focus
STACK     =  Python | Java | C++ | JavaScript | SQL
WEB       =  FastAPI | Flask | Node.js | Express | React | TailwindCSS
AI/ML     =  RAG | Chroma | Scikit-Learn | Prompt Engineering | LLM Evaluation
DATABASES =  MySQL | PostgreSQL | MongoDB
OPEN_TO   =  AI Engineering Internships | New Grad SWE Roles
```

### > ls /tech-stack

**[ Languages ]**
<br />
<img src="https://skillicons.dev/icons?i=python,java,cpp,js&theme=dark" />

<br />

**[ Backend ]**
<br />
<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,express&theme=dark" />

<br />

**[ Frontend ]**
<br />
<img src="https://skillicons.dev/icons?i=react,tailwind,html,css&theme=dark" />

<br />

**[ Databases ]**
<br />
<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb&theme=dark" />

<br />

**[ Tools & DevOps ]**
<br />
<img src="https://skillicons.dev/icons?i=docker,githubactions,vercel,git,github,vscode&theme=dark" />

---

### > cat focus-areas.json

| Domain | Focus | Details |
| :--- | :--- | :--- |
| **AI Engineering** | Applied | RAG pipelines, grounding gates, LLM eval harnesses |
| **Backend Development** | Applied | REST APIs with FastAPI / Flask / Express, relational + document DBs |
| **Frontend Development** | Applied | React + TailwindCSS, Jinja2 server-rendered UIs |
| **DevOps** | Applied | Docker, GitHub Actions CI, Pytest, Vercel / Render deployments |

---

### > cat experience.log

| Role | Organization | Period |
| :--- | :--- | :--- |
| **Artificial Intelligence Intern** | Naviotech Solution Pvt. Ltd. | Jun 2026 – Aug 2026 |
| **AI-ML Virtual Intern** (Grade: Outstanding) | AICTE · EduSkills · Google for Developers | Apr 2026 – Jun 2026 |

---

### > ls /projects --sort=impact

<details open>
<summary><b>▶ RTI Sahayak — Grounded RTI Application Drafter & Statutory Deadline Tracker</b></summary>
<br />
A citizen-facing AI platform that turns plain-language grievance descriptions into legally-grounded Right to Information Act applications, with section-level citations grounded in retrieved statutory text and support for English, Hindi, and Marathi.

**🔗 Live App: [rti-sahayak-smoky.vercel.app](https://rti-sahayak-smoky.vercel.app/)**

| Aspect | Detail |
| :--- | :--- |
| **Stack** | Python · FastAPI · ChromaDB · ONNX MiniLM · Groq · Gemini · Anthropic · Jinja2 |
| **Architecture** | Two-check grounding gate (deterministic statutory retrieval + LLM scope verdict), 3-provider LLM fallback chain, per-IP rate limiting |
| **Corpus** | 81 boundary-aligned chunks covering all 31 sections of the RTI Act |
| **Features** | Clause-level citation chips, statutory deadline tracking (/track), browser-native draft saving, multilingual drafting, PDF export |
| **Eval** | 113-case labeled set: F1 0.63 → 0.95, false refusals 28.3% → 0%; 27-case automated regression suite |
| **Efficiency** | PyTorch → ONNX embeddings cut peak memory to 288 MB (fits a 512 MB tier) |
| **Live** | [rti-sahayak-smoky.vercel.app](https://rti-sahayak-smoky.vercel.app/) |
| **Repo** | [github.com/Pradnesh02/rti-sahayak](https://github.com/Pradnesh02/rti-sahayak) |
</details>

<details open>
<summary><b>▶ DocuMesh — Multi-Agent Compliance Intelligence Platform</b></summary>
<br />
A multi-agent document-intelligence pipeline for compliance analysis, built with an Extractor → Retriever → Risk-Analyst → Verifier/Critic agent chain, backed by hybrid retrieval and a CI-integrated evaluation harness.

| Aspect | Detail |
| :--- | :--- |
| **Stack** | LangGraph · FastAPI · pgvector · LangSmith/Langfuse |
| **Architecture** | 4-agent pipeline: Extractor → Retriever → Risk-Analyst → Verifier |
| **Retrieval** | Hybrid BM25 + dense retrieval with cross-encoder reranking |
| **Eval** | Tracks extraction F1, retrieval recall@k, hallucination rate, cost-per-document |
| **Data** | Real public sources — SEC EDGAR, OFAC sanctions API, GDPR regulatory text |
| **Repo** | [github.com/Pradnesh02/DocuMesh](https://github.com/Pradnesh02/DocuMesh) |
</details>

<details open>
<summary><b>▶ Model Regression Detection System — CI/CD for LLM Behavior</b></summary>
<br />
A CI/CD-style pipeline that tests any LLM-powered feature against a human-labeled golden dataset on every prompt/model change, statistically detects regressions, and blocks merges before bad outputs reach users.

| Aspect | Detail |
| :--- | :--- |
| **Stack** | Python · OpenAI API · SQLite · GitHub Actions · Docker |
| **Eval Engine** | Multi-dimensional scoring — category accuracy, LLM-as-judge relevance, latency, tokens |
| **Statistics** | McNemar's test for paired regression significance, not flat percentage thresholds |
| **Calibration** | LLM-judge validated against human-labeled holdout set before being trusted |
| **CI/CD** | GitHub Action blocks PR merges on critical regressions, posts diff reports to Slack |
| **Repo** | [github.com/Pradnesh02/model-regression-system](https://github.com/Pradnesh02/model-regression-system) |
</details>

<details open>
<summary><b>▶ Blood Bank Web App — AI/ML Healthcare Inventory & Forecasting Platform</b></summary>
<br />
A full-stack blood bank platform with role-based admin/user dashboards, 7-day demand forecasting, ML donor eligibility prediction, low-stock email alerts, and automated PDF reporting.

| Aspect | Detail |
| :--- | :--- |
| **Stack** | Python · Flask · PostgreSQL · SQLAlchemy · Flask-Migrate · scikit-learn · Meta Prophet · Tailwind CSS · Plotly.js |
| **Features** | Demand forecasting, donor eligibility prediction, appointment booking, low-stock alerts, ReportLab PDF reports |
| **Engineering** | Blueprint-based modular routing, Flask-Login + Bcrypt auth, versioned migrations, Pytest-validated flows |
| **Repo** | [github.com/Pradnesh02/Blood-Bank-Web-app](https://github.com/Pradnesh02/Blood-Bank-Web-app) |
</details>

---

### > cat education.log

**[Current]** B.Tech Computer Science & Engineering — D.Y. Patil College of Engineering & Technology, Kolhapur
<br />
Expected May 2027 · CGPA 7.93/10 (through Sem 7)

### > cat achievements.log

- 🏆 Top 5 rank in a regional technical hackathon
- 💻 450+ problems solved on LeetCode (97.4% acceptance rate)
- 📜 Certifications: AI Fluency (Anthropic) · Docker Essentials (IBM) · Foundations of Prompt Engineering (AWS) · Python with DSA Bootcamp (Udemy)

---

### > git stats --global

<div align="center">
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Pradnesh02&theme=dracula" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Pradnesh02&hide_border=true&background=1E1E2E&stroke=CBA6F7&ring=A6E3A1&fire=CBA6F7&currStreakLabel=CBA6F7" />
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Pradnesh02&theme=dracula" />
</div>

### > trophy-case --display

<div align="center">
  <img src="https://github-profile-trophy-nu.vercel.app/?username=Pradnesh02&theme=dracula&no-frame=true&no-bg=true&margin-w=4&title=Commits,Stars,Repositories,Experience" />
</div>

### > activity-graph --timeline

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Pradnesh02&theme=dracula" />
</div>

### > ./snake-animation.sh

<div align="center">
  <img src="https://raw.githubusercontent.com/Pradnesh02/Pradnesh02/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

---

### > cat current-focus.yaml

```yaml
learning:
  - Multi-agent orchestration with LangGraph
  - LLM evaluation methodology (statistical significance, judge calibration)

shipped:
  - RTI-Sahayak               # live: https://rti-sahayak-smoky.vercel.app/

building:
  - DocuMesh                  # multi-agent compliance intelligence platform
  - ModelRegressionSystem     # CI/CD pipeline for LLM regression testing

exploring:
  - Hybrid retrieval systems (BM25 + dense + reranking)
  - Production-grade eval harnesses for LLM applications

open_to:
  - AI Engineering Internships
  - New Grad Software Engineering Roles
```

---

### > ping me

<div align="center">
  <a href="https://www.linkedin.com/in/pradnesh-khasnis-a146a9358/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pradneshkhasnis02@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Pradnesh02"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</div>

<br />

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=1E1E2E&fontColor=CBA6F7" />
</div>
