<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Nesh%20Rochwani&fontSize=52&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Software%20Engineer%20%7C%20Cloud%20%7C%20AI%20Systems&descAlignY=58&descSize=20" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&pause=1000&color=6AD3F7&center=true&vCenter=true&width=720&lines=M.S.+Computer+Science+%40+Illinois+Tech+%E2%80%94+May+2026;Full-Stack+%26+Cloud+Engineer;Building+AI+Agents+%26+Clinical+Intelligence+Systems;AWS+Certified+%7C+Springer+Published+Researcher;Open+to+Full-Time+Opportunities)](https://git.io/typing-svg)

<br/>

[![Location](https://img.shields.io/badge/Chicago%2C%20IL-0078D4?style=flat-square&logo=google-maps&logoColor=white)](#)
[![Email](https://img.shields.io/badge/neshrochwani121%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:neshrochwani121@gmail.com)
[![LinkedIn](https://img.shields.io/badge/nesh--rochwani-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/nesh-rochwani)
[![GitHub](https://img.shields.io/badge/nr1306-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nr1306)

</div>

---

## About

M.S. Computer Science candidate at **Illinois Institute of Technology** (May 2026) with hands-on experience building scalable backend services, cloud applications, and AI-powered systems. I work across the full stack — from serverless AWS pipelines and event-driven backends to multi-agent LLM orchestration and production SaaS APIs.

I've shipped to real users at a production startup (Find Me LLC), built IoT platforms at NXON AI, published two research papers at Springer, and presented at SMARTCOM 2024. I'm most effective at the intersection of systems engineering and applied AI — building things that are reliable, observable, and actually used.

> **Seeking full-time Software Engineering or Cloud Engineering roles · Available May 2026**

---

## Experience

<table>
<tr>
<td width="70%">

### Full Stack Developer · Find Me LLC

</td>
<td width="30%" align="right">

`Jun 2025 – Sep 2025`

</td>
</tr>
</table>

*New York (Remote) · Production SaaS · 4–6 person engineering team*

- Shipped customer-facing platform improvements by hardening core backend APIs with strict validation and OpenAPI regression tests, reducing production defects and enabling faster iteration through safer releases
- Integrated **Apple Sign-In** using OAuth 2.0 and automated release pipelines via **GitLab CI/CD**, standardizing secure authentication across the team
- Designed and maintained REST APIs for a production SaaS — defining request/response contracts, schema validation, and scalable data access patterns using **Node.js, Express, MongoDB**
- Added structured request logging and error analytics (request IDs + standardized error responses) across APIs, speeding up production debugging and reducing repeat incident time

`Node.js` `Express` `MongoDB` `OAuth 2.0` `GitLab CI/CD` `REST APIs` `OpenAPI/Swagger`

<br/>

<table>
<tr>
<td width="70%">

### Software Developer · NXON AI Pvt Ltd

</td>
<td width="30%" align="right">

`Jan 2024 – Jun 2024`

</td>
</tr>
</table>

*Gujarat, India · IoT Control Platform*

- Developed **C++/Qt** software components for an IoT control platform, implementing event-driven device state handling and real-time dashboard updates for 20+ devices
- Engineered **MQTT telemetry** with QoS/retry/backoff and fault-handling, improving message delivery reliability under unstable networks and reducing dropped updates in production
- Built a Python anomaly detection pipeline including data preprocessing, feature extraction, and model evaluation for time-series sensor data
- Collaborated across Agile sprints contributing to design discussions, code reviews, and integration support

`C++` `Qt/QML` `Python` `MQTT` `AWS IoT Core` `Time-Series ML` `Embedded Systems`

<br/>

<table>
<tr>
<td width="70%">

### Research Intern · Charusat University

</td>
<td width="30%" align="right">

`May 2023 – Nov 2023`

</td>
</tr>
</table>

*Gujarat, India · Published at Springer (Jun 2024)*

- Investigated performance tradeoffs between statistical models (ARIMA, Prophet) and deep learning architectures (RNN, GRU, LSTM, DeepAR, Bi-LSTM) across real-world time-series datasets
- Designed evaluation framework using MSE and MAE metrics; preprocessed and cleaned 90,000+ hourly entries from Jena Climate and Energy Consumption datasets
- Demonstrated **12–15% accuracy gain** of deep learning models over traditional statistical approaches, with DeepAR and Bi-LSTM outperforming all baselines

`Python` `TensorFlow` `ARIMA` `Prophet` `LSTM` `DeepAR` `Pandas` `Matplotlib`

---

## Featured Projects

### [ARIA — Adherence Risk Intelligence Agent](https://github.com/nr1306/Aria)

> A full-stack, between-visit clinical intelligence platform for hypertension management. Ingests patient EHR data via FHIR R4, runs a three-layer AI analysis nightly, and delivers a structured pre-visit briefing to the clinician at 7:30 AM on every appointment day — so they walk in already knowing.

![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js%2014-black?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![FHIR](https://img.shields.io/badge/FHIR%20R4-e8734a?style=flat-square)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

- Built an AI-powered pre-visit briefing system for **1,800-patient hypertension panels**, generating risk-stratified summaries before appointments to eliminate manual chart review
- Designed a **three-layer clinical prioritization pipeline**: deterministic rule engine → patient-adaptive risk scoring → LLM-generated briefings, with safety gates controlling when model output surfaces
- Implemented **FHIR R4 ingestion**, drug-class-aware titration windows, drug interaction detection, LLM guardrails, and full audit logging — keeping ARIA as clinician decision support, not autonomous diagnosis
- **583 passing tests** across ingestion, pipeline, and briefing layers; 12 tables, 19 indexes in PostgreSQL

[![View Repo](https://img.shields.io/badge/View%20Repo-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nr1306/Aria)

<br/>

---

### [VentureScope — Multi-Agent Investment Intelligence](https://github.com/nr1306/VentureScope)

> Enter a company name. Four specialized AI agents research the market, financials, competitors, and risks in parallel — then synthesize a structured due diligence report with guardrails, LLM-as-judge evals, and full observability via Langfuse.

![Python](https://img.shields.io/badge/Python%203.12-3776ab?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js%2015-black?style=flat-square&logo=next.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

- Architected a **multi-agent orchestration platform** fanning out 4 async specialist agents in parallel — delivering structured investment reports in **<2 minutes** vs. 3–4× longer sequential execution
- Solved Celery/asyncio event-loop isolation by enforcing per-invocation async clients and SQLAlchemy NullPool — eliminating connection-pool failures under concurrent worker load
- Built a **production eval harness** with 4 deterministic quality metrics and an LLM-as-judge rubric against a 50-company golden dataset; achieved **100% competitor recall** with citation-grounded, hallucination-resistant outputs
- Full observability via Langfuse — every agent step, tool call, and token count traced end-to-end

[![View Repo](https://img.shields.io/badge/View%20Repo-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nr1306/VentureScope)

<br/>

---

### [Ticker — Ambient Desktop Stock Tracker](https://github.com/nr1306/Ticker)

> A lightweight always-on-top desktop widget for working professionals who hold stocks but can't afford distraction. Lives quietly in a corner of your screen — dims to 40% opacity at idle, snaps to full on hover. Live prices, smart alerts, news pulse, and AI insights without the noise.

![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![GPT-4o](https://img.shields.io/badge/GPT--4o-412991?style=flat-square&logo=openai&logoColor=white)
![Yahoo Finance](https://img.shields.io/badge/Yahoo%20Finance-6001D2?style=flat-square)
![NewsAPI](https://img.shields.io/badge/NewsAPI-black?style=flat-square)

- Built an **Electron desktop widget** with frameless always-on-top overlay and background IPC polling (yahoo-finance2, 60s interval) — portfolio and watchlist with live prices, zero browser tab required
- Implemented price alerts (floor/ceiling/% triggers), native system notifications, and persistent unread badge tracking — informed during market moves without disrupting deep work
- Added **SQLite caching**, typed IPC flows, and **GPT-4o**-powered AI recommendations + news summaries — reducing redundant API calls and surfacing 5 actionable insights every morning

[![View Repo](https://img.shields.io/badge/View%20Repo-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nr1306/Ticker)

<br/>

---

### CareBridge — Community Care Coordination Platform

> Replaces calls, texts, and spreadsheets for faith-based coordinators managing non-emergency community needs. AI-assisted intake, intelligent volunteer matching, SMS dispatch, and full audit trail — turning reactive coordination into a structured operational system.

![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio%20SMS-F22F46?style=flat-square&logo=twilio&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-555?style=flat-square)

- Built AI-assisted intake and matching workflows with a mandatory safety screen and a **6-signal volunteer scoring formula** (distance · schedule · skills · rating · language · relationship)
- Implemented **SMS-based dispatch and check-in flows** (Twilio) and automated daily risk scans for unmet needs and missed visits — ensuring no requests fall through the cracks
- Strengthened accountability through **role-based access control**, immutable audit logging, and warm handoff workflows — escalating clinical concerns without exposing unnecessary data

`🔒 Private Repository`

<br/>

---

### [Golazo — AI Companion for the 2026 FIFA World Cup](https://github.com/nr1306/golazo)

> Fan-first AI agent for the 2026 FIFA World Cup across the USA, Canada & Mexico. Chat with the agent, explore predicted lineups, plan your trip, and get crowd vibes for every stadium — all in one place.

![Next.js](https://img.shields.io/badge/Next.js%2014-black?style=flat-square&logo=next.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB%20Atlas-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%202.0%20Flash-4285F4?style=flat-square&logo=google&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)

- Built a **Gemini 2.0 Flash-powered AI chat agent** with smart memory across sessions — covering 16 stadiums, 48 teams, and 104 matches across three host countries
- Implemented **trip planner, fantasy roster, stadium vibes**, and predicted lineup features with MongoDB Atlas Triggers for proactive match result notifications
- Designed an **action approval flow** so AI-suggested bookings require explicit user confirmation — the agent plans, the user decides

[![View Repo](https://img.shields.io/badge/View%20Repo-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nr1306/golazo)

---

## Repository Landscape

<div align="center">

| 🤖 AI & Agentic Systems | ☁️ Cloud & DevOps | 🌐 Full-Stack & Product | 🔬 ML & Research |
|:---:|:---:|:---:|:---:|
| ARIA · VentureScope | AWS-Compliance-Automation | Ticker · Golazo | HeartAttack-Predictor |
| CareBridge · PrepWise | Dental-Data-Pipeline | Portfolio · SpaceData | Gradient-Boosting-Tree |
| MCP-MongoDB-Chatbot | Drone-Trajectory-26 | BMI-Calculator | ElasticNet-Regression |

<br/>

[![Explore All Repositories](https://img.shields.io/badge/⬡%20Explore%20All%20Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nr1306?tab=repositories)

</div>

---

## Tech Stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=py,ts,js,java,cpp,go)](https://skillicons.dev)

`Python` · `TypeScript` · `JavaScript` · `Java` · `C++` · `Go` · `SQL` · `CSS`

<br/>

**Cloud & Infrastructure**

[![Cloud](https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,terraform,linux)](https://skillicons.dev)

`AWS` · `GCP` · `Docker` · `Kubernetes` · `Terraform` · `Serverless` · `CI/CD` · `CloudWatch`

<br/>

**Web & Frameworks**

[![Web](https://skillicons.dev/icons?i=nextjs,react,nodejs,fastapi,express)](https://skillicons.dev)

`Next.js` · `React` · `Node.js` · `FastAPI` · `Express` · `REST APIs` · `OAuth2` · `JWT` · `OpenAPI`

<br/>

**Databases**

[![Databases](https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,mongodb)](https://skillicons.dev)

`PostgreSQL` · `MySQL` · `SQLite` · `Redis` · `MongoDB` · `pgvector` · `FAISS` · `Pinecone`

<br/>

**AI / ML**

[![AI](https://skillicons.dev/icons?i=pytorch,tensorflow)](https://skillicons.dev)

`PyTorch` · `TensorFlow` · `LangChain` · `Prompt Engineering` · `LLM Evaluation` · `Agentic Workflows` · `Scikit-learn` · `NLP` · `PySpark`

</div>

---

## Research Publications

### Deep Learning for Breast Cancer Classification: A Comparative Study of Pretrained CNN Models
**Springer · April 2025** &nbsp;·&nbsp; [View Publication →](https://link.springer.com/chapter/10.1007/978-981-97-8526-1_39)

Conducted a comparative study on six pre-trained CNN architectures (VGG16, ResNet50, Xception, InceptionV3, DenseNet121, DenseNet169) using transfer learning to classify breast cancer from microscopic biopsy images. Evaluated across Adam, RMSprop, and SGD optimizers on a 2,292-image Kaggle dataset (benign vs. malignant).

> **Xception + SGD achieved 99.99% accuracy** · ResNet50 + Adam: 99.8% · Key finding: transfer learning with pre-trained CNNs significantly outperforms training from scratch on limited medical imaging datasets

`Python` `TensorFlow/Keras` `Transfer Learning` `CNN` `Medical Imaging` `NumPy`

<br/>

### Comparing Effectiveness of Statistical Versus Deep Learning for Time Series Forecasting
**Springer · June 2024** &nbsp;·&nbsp; [View Publication →](https://link.springer.com/chapter/10.1007/978-981-97-1313-4_22)

Benchmarked traditional statistical models (ARIMA, Prophet) against deep learning architectures (RNN, GRU, LSTM, DeepAR, Bi-LSTM, Bi-GRU) on two real-world datasets: Jena Climate Dataset (70,080 hourly entries) and Appliances Energy Prediction Dataset (19,735 entries). Evaluated using MSE and MAE.

> **DeepAR and Bi-LSTM outperformed all models** · 12–15% accuracy gain over statistical approaches · Deep learning effectively captured non-linear and long-term temporal dependencies

`Python` `TensorFlow` `ARIMA` `Prophet` `LSTM` `DeepAR` `Bi-GRU` `Pandas` `Matplotlib`

---

## Education

<table>
<tr>
<td>

**Illinois Institute of Technology** — Chicago, IL

`M.S. Computer Science` · GPA 3.4 / 4.0

*Coursework: Medical Informatics & AI · Design & Analysis of Algorithms · Data Mining · Machine Learning · Big Data Technologies*

</td>
<td align="right">

**May 2026**

</td>
</tr>
<tr><td colspan="2"><br/></td></tr>
<tr>
<td>

**Charusat University** — Gujarat, India

`B.Tech Information Technology` · GPA 3.7 / 4.0

*Coursework: Data Structures · Operating Systems · AI · Full-Stack with Spring Boot · Statistical & Numerical Techniques*

</td>
<td align="right">

**May 2024**

</td>
</tr>
</table>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nesh-rochwani)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:neshrochwani121@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nr1306)

<br/>

[![Profile Views](https://visitcount.itsvg.in/api?id=20IT121&label=Profile%20Views&icon=5&color=6&pretty=true)](https://visitcount.itsvg.in)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
