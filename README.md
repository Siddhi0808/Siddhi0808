<div align="center"> <h1>Siddhi Jain</h1> <p><b>Software Engineer &nbsp;·&nbsp; Backend &amp; Full-Stack &nbsp;·&nbsp; C++ &nbsp;·&nbsp; Python &nbsp;·&nbsp; DSA</b></p> <p> Final-year CSE student at UPES. I build backend systems that stay correct under load:<br/> REST APIs on PostgreSQL, transactions and locking, CI pipelines and thorough test suites. </p> <p> <a href="https://www.linkedin.com/in/siddhijain08"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="mailto:siddhij1011@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a> <a href="https://leetcode.com/u/siddhijain008/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/></a> <a href="https://codolio.com/profile/Siddhijain008"><img src="https://img.shields.io/badge/Codolio-334155?style=for-the-badge" alt="Codolio"/></a> </p> </div> <br/> <div align="center"> <table> <tr> <td align="center" width="25%"><h2>1815</h2><sub>LeetCode max rating<br/>top 7.7% globally</sub></td> <td align="center" width="25%"><h2>900+</h2><sub>DSA problems solved<br/>across platforms</sub></td> <td align="center" width="25%"><h2>480+</h2><sub>automated tests<br/>written across projects</sub></td> <td align="center" width="25%"><h2>2</h2><sub>internships<br/>Ezeiatech · DRDO</sub></td> </tr> </table> </div>
Featured projects
Lingo · Duolingo-style learning app

Live Code  <sub>Next.js · TypeScript · FastAPI · SQLAlchemy · SQLite</sub>

Full-stack app with a 22-lesson course, 5 exercise types, XP, streaks and a leaderboard, deployed on Vercel and Render.

All game logic runs on the server, so scores can't be tampered with from the browser.
Each answer is one database transaction; unique constraints block duplicate XP and an optimistic lock protects hearts and gems from concurrent writes.
312 pytest tests. Game rules are pure functions, so streak logic is tested without a database or a real clock.
GroundTruth AI · LLM hallucination detection

Code  <sub>FastAPI · PostgreSQL · pgvector · Llama 3.2 · Docker · GitHub Actions</sub>

REST API that checks an LLM's answer against a 1,900-chunk knowledge base and returns Supported, Hallucinated or Insufficient Evidence, with the evidence attached.

Retrieval with pgvector similarity search; a local Llama 3.2 judge with schema-validated output and a rule-based fallback.
Race-safe ingestion: a database unique constraint blocks duplicate uploads, even when they arrive at the same time. Outages return clear 503s instead of a wrong verdict.
154 tests in CI against SQLite and real Postgres. A held-out evaluation caught an overfit rule engine (90.8% → 72.0%).
CrashGuard AI · system monitoring and crash-risk prediction

Code  <sub>Python · Flask · PostgreSQL · XGBoost · Docker Compose</sub>

Monitoring platform where 5 collector services stream CPU, memory, disk and network data into a 13-table PostgreSQL schema behind a live Flask dashboard.

XGBoost scores crash risk at 0.94 ROC-AUC on a time-ordered holdout.
Found target leakage in the first labelling approach (labels were rules on the same features) and replaced it.
Live predictions fall back to a heuristic score when no trained model is available.
Experience

Software Developer Intern · Ezeiatech Systems  <sub>May 2026 – Jul 2026</sub>

Built a modular hallucination-detection system for LLM outputs using transformer-based NLP models.
Developed preprocessing, training, evaluation and inference pipelines in PyTorch and scikit-learn.

Summer Trainee · DRDO  <sub>May 2025 – Jul 2025 · source</sub>

Built an air-gapped assistant: local LLM chat, PDF Q&A over FAISS, Whisper speech-to-text.
Debugged a server crash caused by FAISS and PyTorch loading conflicting OpenMP runtimes, and a silent text-to-speech failure caused by macOS's main-thread rule. Fixed both by isolating speech in separate worker processes.
Built a 48-question evaluation set (100% Hit@3, 0.87 MRR) and kept a retrieval filter off after it cut held-out accuracy from 100% to 89%.
Problem solving
Platform	Highlights	
LeetCode	Max rating 1815 (top 7.7%) · 23 contests · 596 problems · 200-day badge	Profile
ICPC	Asia Prelims 2026, 3-member team	
HackerRank	5★ in Python	Profile
Codeforces · CodeChef · Code360	Regular practice and contests	CF · CC · Code360
All platforms	900+ problems combined	Codolio
Skills
	
Languages	C++ · Python · SQL · TypeScript
Backend & web	FastAPI · Flask · REST APIs · SQLAlchemy · Pydantic · Next.js · React · Tailwind CSS
Databases	PostgreSQL · pgvector · MySQL · SQLite
Engineering	Git · Docker · Docker Compose · GitHub Actions (CI/CD) · pytest
Concepts	Data Structures & Algorithms · OOP · DB transactions · concurrency control · optimistic locking · system design
AI / ML	PyTorch · scikit-learn · XGBoost · NLP · RAG · vector search · LangChain · Ollama · FAISS
Achievements
ICPC Asia Prelims 2026: competed as part of a 3-member team
LeetCode: max contest rating 1815, top 7.7% globally
HackerRank: 5★ in Python
Certifications: Introduction to AI & ML (IIT Delhi) · DSA in C++ (Coding Ninjas)
<div align="center"> <sub>Open to SDE, backend and full-stack roles · <a href="mailto:siddhij1011@gmail.com">siddhij1011@gmail.com</a> · <a href="https://www.linkedin.com/in/siddhijain08">LinkedIn</a> · <a href="https://codeforces.com/profile/Siddhij">Codeforces</a> · <a href="https://codolio.com/profile/Siddhijain008">Codolio</a></sub> </div>
