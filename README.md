<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:132f4c,100:58a6ff&height=160&section=header&text=Lucas%20Gonçalves&fontSize=48&fontColor=58a6ff&fontAlignY=38&desc=AI%20Engineer%20·%20LLM%20Agents%20·%20RAG%20·%20Data%20Pipelines%20on%20GCP&descAlignY=58&descSize=16&descColor=8b949e" width="100%"/>
</div>

<div align="center">

**AI Engineer building LLM agents, RAG systems and data pipelines on GCP.**
I work on the part after the model works: grounding, verification, and the limits that keep it honest.

`Open to remote roles, international or Brazil-based` · `GMT-3`

<a href="https://www.linkedin.com/in/lucas-goncalvessz/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://lukesz-portifolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>

</div>

##

### Open source

| | What it is | Proof | Stack |
|---|---|---|---|
| [**sb100_agents**](https://github.com/LukeSantossz/sb100_agents) | Self-hostable RAG API that scores its own confidence | Agent gate calibrated to **96.7% / 3.3%** TPR-FPR · 372 tests, 89.8% coverage · 15 ADRs | `Python` `FastAPI` `Qdrant` `Ollama` `LangGraph` |
| [**tweet-sentiment**](https://github.com/LukeSantossz/tweet-sentiment-analysis) | Sentiment classification fine-tuned end to end | **0.887 macro F1**, +51.9% over the frozen-features baseline · **28.5× faster** Rust preprocessing, parity validated at 3 scales | `Python` `Rust` `PyTorch` `Polars` |
| [**weather-forecast**](https://github.com/LukeSantossz/weather-forecast) | scikit-learn model running in the browser | **Matched to 1e-6** against Python · 200-tree forest serialized and traversed in TypeScript · test-first across 20+ features, traceable in the log | `Python` `TypeScript` `LightGBM` |
| [**visiosoil-app**](https://github.com/LukeSantossz/visiosoil-app) | Soil texture from a photo, fully offline | **3rd of 1,300+** at FETEPS 2025 · paper published at ICPA/ConBAP 2026 · on-device inference in a killable isolate, group-aware dataset splits | `Flutter` `Dart` `TFLite` |
| [**my-framework**](https://github.com/LukeSantossz/my-framework) | Engineering standards, enforced inside AI agents | Cross-provider review gate · 101 shell tests · reused across 5 repositories | `Bash` `Node.js` `GitHub Actions` |
| [**AutoMQ** `#3261`](https://github.com/AutoMQ/automq/pull/3261) | Accepted contribution to a Kafka-compatible streaming platform | Response-size validation so a request/response mismatch **fails cleanly instead of crashing**, shipped with **157 lines of tests** | `Java` |

### Built at work

Closed source. Numbers verified against the repositories I contributed to.

| | What it is | Proof | Stack |
|---|---|---|---|
| **Agent code-generation platform** | Spec in, working application out | **Seven specialist agents** under a coordinator that delegates · generated code isolated in per-job micro-VMs · release verdict from **deterministic scanner receipts**, not the model | `Python` `LangGraph` `Kata` `Cloud Run` |
| **AI advising platform** | Grounded answers over institutional data | Hybrid retrieval **built from scratch** over pgvector · refuse-before-call gate and post-answer verifier · **1,149 tests** | `Python` `FastAPI` `pgvector` `Anthropic` |

##

### My AI Engineering Stack

<div align="center">

**`Agents & Orchestration`**
<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
</p>

**`RAG & Retrieval`**
<p>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white"/>
</p>

**`ML & Inference`**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/TF%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
</p>

**`Backend & Data`**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
</p>

**`Cloud Data`**
<p>
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloud%20Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dataflow-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge"/>
</p>

**`Infra & Quality`**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

</div>

### GitHub Activity

<div align="center">
<a href="https://github.com/LukeSantossz">
  <img src="https://streak-stats.demolab.com?user=LukeSantossz&theme=github-dark-blue&hide_border=true&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&background=0d1117&dates=8b949e&sideLabels=8b949e&currStreakNum=58a6ff&sideNums=58a6ff" />
</a>

<br/><br/>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,50:132f4c,100:0d1117&height=100&section=footer" width="100%"/>
