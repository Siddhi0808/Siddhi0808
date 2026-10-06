<p align="center">
<img src="./assets/banner.svg" width="100%" alt="Siddhi Jain — Software Engineer · Backend & Full-Stack · C++ · Python · DSA"/>
</p>
<p align="center">
I build backend systems that stay correct under load: REST APIs on PostgreSQL, database transactions and locking,<br/>
CI pipelines and thorough test suites. Backed by strong DSA in C++, with hands-on AI/ML work on the side.
</p>
<p align="center">
<a href="https://www.linkedin.com/in/siddhijain08"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/siddhijain008/"><img src="https://img.shields.io/badge/LeetCode-1815-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
<a href="https://codolio.com/profile/Siddhijain008"><img src="https://img.shields.io/badge/All_coding_profiles-6366F1?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codolio"/></a>
<a href="mailto:siddhij1011@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>
<br/>
<p align="center">
<img src="./assets/snapshot.svg" width="100%" alt="LeetCode max rating 1815 (top 7.7%) · 900+ problems solved · 480+ automated tests · 2 internships"/>
</p>
Problem solving
<table>
<tr>
<td width="33%" valign="top">
<img src="https://cdn.simpleicons.org/leetcode/FFA116" width="22" alt=""/>  <b>LeetCode</b><br/>
<sub>Max rating <b>1815</b> · top 7.7%<br/>23 contests · 596 problems · 200-day badge</sub><br/><br/>
<a href="https://leetcode.com/u/siddhijain008/"><img src="https://img.shields.io/badge/View_profile-161B22?style=flat-square&logo=leetcode&logoColor=FFA116" alt="LeetCode profile"/></a>
</td>
<td width="33%" valign="top">
<img src="https://cdn.simpleicons.org/codeforces/1F8ACB" width="22" alt=""/>  <b>Codeforces</b><br/>
<sub>Rated contests and practice<br/>handle: Siddhij</sub><br/><br/>
<a href="https://codeforces.com/profile/Siddhij"><img src="https://img.shields.io/badge/View_profile-161B22?style=flat-square&logo=codeforces&logoColor=1F8ACB" alt="Codeforces profile"/></a>
</td>
<td width="33%" valign="top">
<img src="https://cdn.simpleicons.org/codechef/B9875C" width="22" alt=""/>  <b>CodeChef</b><br/>
<sub>Rated contests<br/>handle: sids1008</sub><br/><br/>
<a href="https://www.codechef.com/users/sids1008"><img src="https://img.shields.io/badge/View_profile-161B22?style=flat-square&logo=codechef&logoColor=B9875C" alt="CodeChef profile"/></a>
</td>
</tr>
<tr>
<td valign="top">
<img src="https://cdn.simpleicons.org/hackerrank/00EA64" width="22" alt=""/>  <b>HackerRank</b><br/>
<sub>5★ gold badge in Python</sub><br/><br/>
<a href="https://www.hackerrank.com/profile/siddhij1011"><img src="https://img.shields.io/badge/View_profile-161B22?style=flat-square&logo=hackerrank&logoColor=00EA64" alt="HackerRank profile"/></a>
</td>
<td valign="top">
<b>🥷  Code360</b><br/>
<sub>Coding Ninjas practice<br/>DSA in C++ certified</sub><br/><br/>
<a href="https://www.naukri.com/code360/profile/59d8f63e-c5af-4400-bfcb-17dd7ff5db96"><img src="https://img.shields.io/badge/View_profile-161B22?style=flat-square" alt="Code360 profile"/></a>
</td>
<td valign="top">
<b>🌏  ICPC</b><br/>
<sub>Asia Prelims 2026<br/>3-member team</sub><br/><br/>
<a href="https://codolio.com/profile/Siddhijain008"><img src="https://img.shields.io/badge/All_platforms_on_Codolio-161B22?style=flat-square" alt="Codolio"/></a>
</td>
</tr>
</table>
Featured projects
<table>
<tr>
<td>
<h3>🦉  Lingo</h3>
<b>Duolingo-style language-learning app</b> · full-stack, deployed on Vercel and Render<br/><br/>
<img src="https://img.shields.io/badge/Next.js-161B22?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript"/>
<img src="https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI"/>
<img src="https://img.shields.io/badge/SQLAlchemy-161B22?style=flat-square&logo=sqlalchemy&logoColor=D71F00" alt="SQLAlchemy"/>
<img src="https://img.shields.io/badge/pytest-161B22?style=flat-square&logo=pytest&logoColor=0A9EDC" alt="pytest"/>
<ul>
<li>All game logic runs on the server, so XP and scores can't be tampered with from the browser.</li>
<li>Each answer is <b>one database transaction</b>: <b>unique constraints</b> block duplicate XP, and an <b>optimistic lock</b> protects hearts and gems from concurrent writes.</li>
<li><b>312 pytest tests</b>. Game rules are pure functions, so streak logic is tested without a database or real clock.</li>
</ul>
<a href="https://github.com/Siddhi0808/duolingo-scalerlabs"><img src="https://img.shields.io/badge/View_code-6366F1?style=for-the-badge&logo=github&logoColor=white" alt="View code"/></a>
<a href="https://duolingo-scalerlabs.vercel.app/"><img src="https://img.shields.io/badge/Live_demo-0891B2?style=for-the-badge&logo=vercel&logoColor=white" alt="Live demo"/></a>
</td>
</tr>
</table>
<table>
<tr>
<td>
<h3>🔍  GroundTruth AI</h3>
<b>REST API that flags LLM answers not backed by your documents</b> · Supported / Hallucinated / Insufficient Evidence<br/><br/>
<img src="https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI"/>
<img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/pgvector-161B22?style=flat-square" alt="pgvector"/>
<img src="https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker"/>
<img src="https://img.shields.io/badge/GitHub_Actions-161B22?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions"/>
<ul>
<li>Retrieves evidence from a 1,900-chunk knowledge base with <b>pgvector</b> search, then a local Llama 3.2 judge decides, with schema-validated output and a rule-based fallback.</li>
<li><b>Race-safe ingestion</b>: a database unique constraint blocks duplicate uploads, even when they arrive at the same time. Outages return a clear 503 instead of a wrong verdict.</li>
<li><b>154 tests in CI</b> against SQLite and real Postgres. A held-out evaluation caught an overfit rule engine (<b>90.8% → 72.0%</b>).</li>
</ul>
<a href="https://github.com/Siddhi0808/GroundTruth_AI"><img src="https://img.shields.io/badge/View_code-6366F1?style=for-the-badge&logo=github&logoColor=white" alt="View code"/></a>
</td>
</tr>
</table>
<table>
<tr>
<td>
<h3>🛡️  CrashGuard AI</h3>
<b>System monitoring with live crash-risk scoring</b> · collectors, PostgreSQL, Flask dashboard, ML<br/><br/>
<img src="https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB" alt="Python"/>
<img src="https://img.shields.io/badge/Flask-161B22?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/XGBoost-161B22?style=flat-square" alt="XGBoost"/>
<img src="https://img.shields.io/badge/Docker_Compose-161B22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker Compose"/>
<ul>
<li>5 collector services stream CPU, memory, disk and network data into a <b>13-table PostgreSQL schema</b> behind a live dashboard.</li>
<li>XGBoost scores crash risk at <b>0.94 ROC-AUC</b> on a time-ordered holdout, after finding and removing <b>target leakage</b> in the first labelling approach.</li>
<li>Live predictions fall back to a heuristic score when no trained model is available.</li>
</ul>
<a href="https://github.com/Siddhi0808/CrashGuardAI"><img src="https://img.shields.io/badge/View_code-6366F1?style=for-the-badge&logo=github&logoColor=white" alt="View code"/></a>
</td>
</tr>
</table>
Experience
<table>
<tr>
<td width="50%" valign="top">
<b>Software Developer Intern</b><br/>
<sub>Ezeiatech Systems · May 2026 – Jul 2026</sub>
<ul>
<li>Built a modular <b>hallucination-detection system</b> for LLM outputs using transformer-based NLP models.</li>
<li>Developed preprocessing, training, evaluation and inference pipelines in PyTorch and scikit-learn.</li>
</ul>
<img src="https://img.shields.io/badge/PyTorch-161B22?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch"/>
<img src="https://img.shields.io/badge/scikit--learn-161B22?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/NLP-161B22?style=flat-square" alt="NLP"/>
</td>
<td width="50%" valign="top">
<b>Summer Trainee</b><br/>
<sub>DRDO · May 2025 – Jul 2025 · <a href="https://github.com/Siddhi0808/PrivaEdge">PrivaEdge</a></sub>
<ul>
<li>Built an <b>air-gapped AI assistant</b>: local LLM chat, PDF Q&A over FAISS, Whisper speech-to-text.</li>
<li>Debugged a server crash caused by <b>conflicting OpenMP runtimes</b> (FAISS + PyTorch) and a silent macOS speech bug; fixed both with worker processes.</li>
<li>48-question evaluation: <b>100% Hit@3</b>, 0.87 MRR.</li>
</ul>
<img src="https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB" alt="Python"/>
<img src="https://img.shields.io/badge/Ollama-161B22?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"/>
<img src="https://img.shields.io/badge/FAISS-161B22?style=flat-square" alt="FAISS"/>
</td>
</tr>
</table>
Tech stack
<table>
<tr>
<td><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/C++-161B22?style=flat-square&logo=cplusplus&logoColor=00599C" alt="C++"/>
<img src="https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB" alt="Python"/>
<img src="https://img.shields.io/badge/SQL-161B22?style=flat-square" alt="SQL"/>
<img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript"/>
</td>
</tr>
<tr>
<td><b>Backend</b></td>
<td>
<img src="https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI"/>
<img src="https://img.shields.io/badge/Flask-161B22?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/REST_APIs-161B22?style=flat-square" alt="REST APIs"/>
<img src="https://img.shields.io/badge/SQLAlchemy-161B22?style=flat-square&logo=sqlalchemy&logoColor=D71F00" alt="SQLAlchemy"/>
<img src="https://img.shields.io/badge/Pydantic-161B22?style=flat-square&logo=pydantic&logoColor=E92063" alt="Pydantic"/>
</td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td>
<img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
<img src="https://img.shields.io/badge/Next.js-161B22?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-161B22?style=flat-square&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS"/>
</td>
</tr>
<tr>
<td><b>Databases</b></td>
<td>
<img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/pgvector-161B22?style=flat-square" alt="pgvector"/>
<img src="https://img.shields.io/badge/MySQL-161B22?style=flat-square&logo=mysql&logoColor=4479A1" alt="MySQL"/>
<img src="https://img.shields.io/badge/SQLite-161B22?style=flat-square&logo=sqlite&logoColor=44A0E0" alt="SQLite"/>
</td>
</tr>
<tr>
<td><b>DevOps & testing</b></td>
<td>
<img src="https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker"/>
<img src="https://img.shields.io/badge/GitHub_Actions-161B22?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/pytest-161B22?style=flat-square&logo=pytest&logoColor=0A9EDC" alt="pytest"/>
<img src="https://img.shields.io/badge/Git-161B22?style=flat-square&logo=git&logoColor=F05032" alt="Git"/>
</td>
</tr>
<tr>
<td><b>AI / ML</b></td>
<td>
<img src="https://img.shields.io/badge/PyTorch-161B22?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch"/>
<img src="https://img.shields.io/badge/scikit--learn-161B22?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/XGBoost-161B22?style=flat-square" alt="XGBoost"/>
<img src="https://img.shields.io/badge/RAG_·_FAISS_·_Ollama-161B22?style=flat-square" alt="RAG, FAISS, Ollama"/>
</td>
</tr>
<tr>
<td><b>Core CS</b></td>
<td><sub>Data Structures & Algorithms · OOP · database transactions · concurrency control · system design</sub></td>
</tr>
</table>
Achievements
<table>
<tr>
<td align="center" width="25%">🌏<br/><b>ICPC Asia Prelims</b><br/><sub>2026 · 3-member team</sub></td>
<td align="center" width="25%">🥇<br/><b>LeetCode 1815</b><br/><sub>Max rating · top 7.7%</sub></td>
<td align="center" width="25%">⭐<br/><b>HackerRank 5★</b><br/><sub>Python</sub></td>
<td align="center" width="25%">📜<br/><b>Certifications</b><br/><sub>AI & ML (IIT Delhi)<br/>DSA in C++ (Coding Ninjas)</sub></td>
</tr>
</table>
<br/>
<p align="center">
<b>Open to SDE, backend and full-stack roles.</b><br/><br/>
<a href="https://www.linkedin.com/in/siddhijain08"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:siddhij1011@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://leetcode.com/u/siddhijain008/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
<a href="https://codeforces.com/profile/Siddhij"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
<a href="https://codolio.com/profile/Siddhijain008"><img src="https://img.shields.io/badge/Codolio-6366F1?style=for-the-badge" alt="Codolio"/></a>
</p>
