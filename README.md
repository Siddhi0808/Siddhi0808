<div align="center">
Hi, I'm Siddhi Jain 👋
Backend-focused Software Engineer · Final-year B.Tech CSE (AI & ML) @ UPES
<p>
<a href="https://www.linkedin.com/in/siddhijain08"><img src="https://img.shields.io/badge/LinkedIn-siddhijain08-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:siddhij1011@gmail.com"><img src="https://img.shields.io/badge/Email-siddhij1011-1E293B?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://leetcode.com/u/Siddhijain008/"><img src="https://img.shields.io/badge/LeetCode-1815-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
<a href="https://duolingo-scalerlabs.vercel.app/"><img src="https://img.shields.io/badge/Live_Project-Lingo-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Live project"/></a>
</p>
<p>
<img src="https://img.shields.io/badge/Open_to-SDE_Roles-7C3AED?style=flat-square" alt="Open to SDE roles"/>
<img src="https://img.shields.io/badge/Graduating-2027-1E293B?style=flat-square" alt="Graduating 2027"/>
<img src="https://img.shields.io/badge/Based_in-Delhi_|_Dehradun-334155?style=flat-square" alt="Location"/>
</p>
</div>
🧑‍💻 About Me
I'm a final-year Computer Science student at UPES, Dehradun (CGPA 8.12), with internships at Ezeiatech and DRDO. I like building backends that stay correct under pressure: database transactions, concurrency control, CI and solid test suites. I also work in AI/ML (RAG, vector search, local LLMs), and I care about evaluating models honestly on held-out data.
⚙️ Built and deployed full-stack and backend systems with 480+ automated tests across projects
🧠 Strong in DSA and C++: LeetCode max rating 1815, 900+ problems solved
🎯 Currently looking for Software Development Engineer roles
🏆 Achievements
<table>
<tr>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/ICPC-Asia_Prelims_2026-1E293B?style=for-the-badge" alt="ICPC"/><br/>
<sub>Competed as part of a 3-member team</sub>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/LeetCode-Max_Rating_1815-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode rating"/><br/>
<sub>Contest rating on LeetCode</sub>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/Problems_Solved-900%2B-7C3AED?style=for-the-badge" alt="900+ problems"/><br/>
<sub>Across LeetCode, Codeforces and Code360</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/HackerRank-5★_Python-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black" alt="HackerRank"/><br/>
<sub>Gold badge in Python</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Certified-AI_%26_ML-334155?style=for-the-badge" alt="AI and ML certificate"/><br/>
<sub>Introduction to AI & ML, IIT Delhi</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Certified-DSA_in_C%2B%2B-334155?style=for-the-badge" alt="DSA certificate"/><br/>
<sub>Coding Ninjas</sub>
</td>
</tr>
</table>
💼 Experience
Software Developer Intern · Ezeiatech Systems Pvt. Ltd.   <sub>May 2026 – Jul 2026</sub>
Built a modular hallucination-detection system for LLM outputs using transformer-based NLP models.
Developed preprocessing, training, evaluation and inference pipelines in PyTorch and scikit-learn.
Summer Trainee · DRDO   <sub>May 2025 – Jul 2025</sub>
Built an air-gapped AI assistant: local Llama 3.2 chat, PDF Q&A over FAISS, and Whisper speech-to-text.
Built a 48-question evaluation (100% Hit@3, 0.87 MRR) and rejected a filter that cut held-out accuracy to 89%.
Fixed an OpenMP runtime crash (FAISS + PyTorch) by isolating speech processing in worker processes.
🚀 Featured Projects
<table>
<tr>
<td width="50%" valign="top">
<h3>🦉 Lingo</h3>
<p><b><i>Can a language app keep scores correct when the same user acts from two tabs at once?</i></b></p>
<p>Full-stack Duolingo-style app with a 22-lesson course and 5 exercise types. All scoring stays on the server: each answer is one database transaction, and an optimistic lock protects hearts and gems from concurrent writes. Backed by <b>312 pytest tests</b>.</p>
<p>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white"/>
</p>
<a href="https://duolingo-scalerlabs.vercel.app/"><b>Live Demo →</b></a>  · 
<a href="https://github.com/Siddhi0808/duolingo-scalerlabs"><b>View Project →</b></a>
</td>
<td width="50%" valign="top">
<h3>🔍 GroundTruth AI</h3>
<p><b><i>How do you tell when an LLM's answer isn't backed by your documents?</i></b></p>
<p>REST API that checks LLM answers against a 1,900-chunk knowledge base using pgvector search and a local Llama 3.2 judge, with a rule-based fallback. Held-out testing exposed an overfit rule engine (<b>90.8% → 72.0%</b>). <b>154 tests</b> run in CI against real Postgres.</p>
<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/pgvector-334155?style=flat-square"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>
<a href="https://github.com/Siddhi0808/GroundTruth_AI"><b>View Project →</b></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🔒 Offline AI Assistant</h3>
<p><b><i>Can an AI assistant work fully offline, with no data leaving the machine?</i></b></p>
<p>Privacy-first assistant built at DRDO for air-gapped use: local LLM chat, document Q&A over FAISS vector search, and speech input and output. Evaluated on a 48-question labelled set with <b>100% Hit@3</b>.</p>
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
</p>
<a href="https://github.com/Siddhi0808/OFFLINE-AI-ASSISTANT"><b>View Project →</b></a>
</td>
<td width="50%" valign="top">
<h3>🛡️ CrashGuard AI</h3>
<p><b><i>Can we spot a system heading towards a crash before it happens?</i></b></p>
<p>Monitoring platform with 5 collector services, a 13-table PostgreSQL schema and a live Flask dashboard. Scores crash risk with XGBoost at <b>0.94 ROC-AUC</b>, after finding and removing target leakage in the first labelling approach.</p>
<p>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>
<a href="https://github.com/Siddhi0808/CrashGuardAI"><b>View Project →</b></a>
</td>
</tr>
</table>
🛠️ Tech Stack
Languages
<p>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-334155?style=for-the-badge&logo=databricks&logoColor=white"/>
</p>
Backend & Web
<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white"/>
<img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
</p>
Databases
<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/pgvector-334155?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
</p>
DevOps & Tools
<p>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black"/>
</p>
AI / ML
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-7C3AED?style=for-the-badge"/>
</p>
🧩 Competitive Programming
<p>
<a href="https://leetcode.com/u/Siddhijain008/"><img src="https://img.shields.io/badge/LeetCode-Max_1815-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<img src="https://img.shields.io/badge/Codeforces-Active-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/>
<img src="https://img.shields.io/badge/Code360-Coding_Ninjas-F78C40?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ICPC-Asia_Prelims_2026-1E293B?style=for-the-badge"/>
</p>
<a href="https://leetcode.com/u/Siddhijain008/">
<img src="https://leetcard.jacoblin.cool/Siddhijain008?theme=light&font=Inter&ext=contest" alt="LeetCode stats"/>
</a>
<div align="center">
📫 Connect With Me
<a href="https://www.linkedin.com/in/siddhijain08"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:siddhij1011@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://leetcode.com/u/Siddhijain008/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<a href="https://github.com/Siddhi0808"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<sub>Open to SDE roles and internships · Always happy to talk backend, databases and DSA</sub>
</div>
