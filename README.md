<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=shark&color=1E1E2E&fontColor=CBA6F7&text=%3E_%20PRADNESH%20KHASNIS&fontSize=38&desc=AI-Focused%20Software%20Engineer%20%E2%80%94%20Final%20Year%20CSE&descColor=A6E3A1&animation=fadeIn&fontAlignY=35&descAlignY=55" />
  <br />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=800&color=CBA6F7&center=true&vCenter=true&width=820&lines=%24+whoami+%E2%86%92+CSE+Student+%7C+AI+Engineering;%24+skills+%E2%86%92+Python+%7C+Java+%7C+React+%7C+Node.js;%24+cat+building.txt+%E2%86%92+Multi-agent+%2B+Eval+Systems;%24+status+%E2%86%92+Open+to+Internships+%2F+New+Grad+Roles" />
  <br /><br />

  <a href="https://github.com/Pradnesh02"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://linkedin.com/in/pradnesh02"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pradneshkhasnis@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>

<br />

> **whoami**

Final-year Computer Science & Engineering student focused on AI engineering — I build production-style systems, not just tutorials. My recent work centers on multi-agent LLM pipelines and evaluation infrastructure: systems that don't just generate outputs, but verify, score, and catch their own regressions before they ship.

```bash
$ cat .profile

ROLE      =  CSE Student (Final Year) — AI Engineering Focus
STACK     =  Python | Java | C++ | JavaScript | React | Node.js
DATABASES =  MySQL | PostgreSQL | MongoDB
INTEREST  =  Multi-agent systems | LLM eval & observability | Full-stack AI apps
OPEN_TO   =  AI Engineering Internships | New Grad SWE Roles
```

### > ls /tech-stack

**[ Languages ]**
<br />
<img src="https://skillicons.dev/icons?i=python,java,cpp,js&theme=dark" />

<br />

**[ Backend ]**
<br />
<img src="https://skillicons.dev/icons?i=nodejs,express&theme=dark" />

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
<img src="https://skillicons.dev/icons?i=docker,vscode,git,github&theme=dark" />

---

### > cat focus-areas.json

| Domain | Focus | Details |
| :--- | :--- | :--- |
| **AI Engineering** | Applied | Multi-agent pipelines, RAG, LLM eval harnesses |
| **Backend Development** | Applied | REST APIs with Node.js/Express, relational + document DBs |
| **Frontend Development** | Applied | React + TailwindCSS component-driven UIs |
| **DevOps Fundamentals** | Learning | Docker containerization, CI/CD basics |

---

### > ls /projects --sort=impact

<details open>
<summary><b>▶ RTI Sahayak — Grounded RTI Application Drafter & Statutory Deadline Tracker</b></summary>
<br />
A citizen-facing AI platform that turns plain-language grievance descriptions into legally-grounded Right to Information Act applications, featuring two-check statutory grounding, clause-level citation provenance, and statutory deadline tracking.

| Aspect | Detail |
| :--- | :--- |
| **Stack** | Python · FastAPI · Streamlit · ChromaDB · Groq · Gemini · Anthropic · Jinja2 |
| **Architecture** | Two-check grounding design (corpus health check + LLM scope classifier), 3-provider resiliency fallback chain |
| **Features** | Clause-level citation chips, statutory deadline tracking (/track), browser-native draft saving, multilingual support, PDF export |
| **Eval & Scope** | Evaluated on 113-case dataset (0.000 false refusal rate vs 0.283 baseline), 27-case automated regression suite |
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
<summary><b>▶ Blood Bank Web App &mdash; AI/ML Healthcare Inventory & Forecasting Platform</b></summary>
<br />
An AI-driven blood bank platform featuring demand forecasting, ML donor eligibility tracking, weight validation, appointment booking, and automated healthcare inventory fulfillment.

| Aspect | Detail |
| :--- | :--- |
| **Stack** | Python · Flask · PostgreSQL · scikit-learn (RandomForest) · Meta Prophet · Tailwind CSS · Plotly.js |
| **Features** | AI demand forecasting, ML donor eligibility tracking, appointment booking, weight validation & campaign notice board |
| **Use Case** | Automating blood supply forecasting, donor eligibility verification, and critical healthcare inventory fulfillment |
| **Repo** | [github.com/Pradnesh02/Blood-Bank-Web-app](https://github.com/Pradnesh02/Blood-Bank-Web-app) |
</details>

---

### > cat education.log

**[Current]** B.E. Computer Science & Engineering — Final Year

---

### > git stats --global

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Pradnesh02&show_icons=true&hide_border=true&title_color=CBA6F7&icon_color=A6E3A1&text_color=CDD6F4&bg_color=1E1E2E" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Pradnesh02&hide_border=true&background=1E1E2E&stroke=CBA6F7&ring=A6E3A1&fire=CBA6F7&currStreakLabel=CBA6F7" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pradnesh02&layout=compact&hide_border=true&langs_count=8&title_color=CBA6F7&text_color=CDD6F4&bg_color=1E1E2E" />
</div>

### > trophy-case --display

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Pradnesh02&theme=dracula&no-frame=true&no-bg=true&margin-w=4&column=7" />
</div>

### > activity-graph --timeline

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Pradnesh02&bg_color=1E1E2E&color=CBA6F7&line=A6E3A1&point=CBA6F7&area=true&area_color=313244&hide_border=true" />
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

building:
  - RTI-Sahayak               # grounded RTI application drafter & deadline tracker
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
  <a href="https://linkedin.com/in/pradnesh02"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pradneshkhasnis@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Pradnesh02"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</div>

<br />

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=1E1E2E&fontColor=CBA6F7" />
</div>
