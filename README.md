<div align="center">

# Hi, I'm Somu 👋

**AI engineer and risk-analytics lead.** 14 years in banking analytics (fraud, AML, credit risk, CCAR/CECL),
now building AI systems with LLMs, RAG and MCP that run every day in the cloud.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-srinivasaraosomu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srinivasaraosomu/)
![Open to AI engineering roles](https://img.shields.io/badge/Open_to-AI_engineering_roles-0CAA41?style=for-the-badge)

</div>

---

## 🧭 Job Search Copilot

**Find the right jobs, tailor an honest resume for each one, prepare for the interview, and track it all from your inbox.**
Runs daily on Oracle Cloud, with a Telegram bot. Built for job seekers and for staffing firms managing a whole bench.

[![Watch the 4-minute product tour](https://raw.githubusercontent.com/somu-analyst/Job-Search-Copilot/main/assets/demo_poster.jpg)](https://somu-analyst.github.io/Job-Search-Copilot/#tour)

▶ [2-minute pitch](https://github.com/somu-analyst/Job-Search-Copilot/blob/main/assets/pitch.mp4) · ▶ [4-minute product tour](https://somu-analyst.github.io/Job-Search-Copilot/#tour) · 🌐 [Website](https://somu-analyst.github.io/Job-Search-Copilot/) · 📂 [Showcase repo](https://github.com/somu-analyst/Job-Search-Copilot)

- **Finds jobs from 40+ sources:** employer career systems (Greenhouse, Lever, Ashby, Workday), job-search APIs, job boards, staffing vendors, Google Groups and Gmail job alerts, scored against each person's resume.
- **Tailors truthfully:** RAG matches every requirement to real experience, and a grounding check blocks any claim the resume can't back up.
- **Interview coach:** quizzes, mock video interviews, and AI review of a recorded interview (local speech-to-text and graded answers).
- **Tracks itself:** reads employer replies through the Gmail API and moves each application forward.
- **For staffing firms:** one job pool with a profile per consultant, plus a preview of AI talent outreach by email, SMS and voicemail.

`Python` `FastAPI` `Streamlit` `SQLite` `RAG` `sentence-transformers` `LLMs (free-model failover)` `Playwright` `Gmail API` `Telegram Bot API` `Oracle Cloud` `systemd` `GitHub Actions` `pytest`

---

## 📊 WallStreet Agentic TradeOps

**An options-intelligence terminal that turns NYSE/CBOE options-chain data into explained trade signals**, delivered through a Telegram bot and a Streamlit web terminal.

[![WallStreet AI Ops teaser](https://raw.githubusercontent.com/somu-analyst/WallStreet_Agentic_TradeOps/main/assets/media/next/teaser.gif)](https://somu-analyst.github.io/WallStreet_Agentic_TradeOps/)

▶ [2-minute video tour](https://github.com/somu-analyst/WallStreet_Agentic_TradeOps/blob/main/assets/media/dashboard-full-tour.mp4) · 🌐 [Website](https://somu-analyst.github.io/WallStreet_Agentic_TradeOps/) · 📂 [Showcase repo](https://github.com/somu-analyst/WallStreet_Agentic_TradeOps)

- Open-interest flow, dealer gamma positioning and a 24-model signal ensemble, with Black–Scholes and Monte Carlo pricing.
- A forward-tested accuracy layer weights each model by its recent hit rate; walk-forward checks catch signals that only fit noise.
- Data from more than 15 market and macro APIs; an LLM gateway across Claude, Groq, Gemini and OpenRouter that fails over automatically; an MCP server that gives AI agents read-only access.

`Python` `Streamlit` `Telegram Bot API` `SQLite` `MCP (Python SDK)` `Docker` `LLM gateway` `Oracle Cloud` `CI/CD`

---

## 🗣️ Avatar AI

**A private voice assistant with a lip-synced 3D avatar** that runs on a local LLM by default: interrupt it any time, ask for live data, talk in English, Hindi or Telugu.

[![Avatar AI](https://raw.githubusercontent.com/somu-analyst/Avatar_AI_Agent/main/docs/images/avatars.png)](https://github.com/somu-analyst/Avatar_AI_Agent)

`Python` `FastAPI` `WebSockets` `Ollama` `faster-whisper` `function calling` `three.js (TalkingHead)`

---

## 🔨 Currently building

- **Talent Outreach** for consulting firms: a client requirement in, the right people found and contacted by email, SMS and voicemail.
- **"Preparing for" in Interview Prep:** pick the job you're interviewing for and every practice tab follows it.
- **Licensed job-data routes,** so the copilot depends less on any single job board.

## 🧰 Toolbox

**AI:** LLMs · RAG · embeddings · vector search · MCP · agents · prompt engineering · guardrails and evaluation
**Data:** Python · SQL · SAS · PySpark · Databricks · Snowflake · BigQuery
**Engineering:** FastAPI · Streamlit · Playwright · Docker · GitHub Actions · Oracle Cloud · Linux
**Domain:** credit risk · fraud and AML · CCAR/CECL · loss forecasting · lending analytics
