<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Selma Koudia — AI Engineer"/>

<a href="https://github.com/selmakoudia03">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=780&height=40&lines=%3E+Building+autonomous+multi-agent+systems+%26+state+graphs;%3E+Engineering+hybrid+GraphRAG+%26+enterprise+Text-to-SQL;%3E+Serving+local+LLMs+with+vLLM+%2F+llama.cpp;%3E+Hardening+LLM+apps+against+prompt+injection" alt="typing"/>
</a>

<a href="https://github.com/selmakoudia03"><img src="https://img.shields.io/badge/GitHub-selmakoudia03-0D1117?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/VOTRE-SLUG/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=selmakoudia03&style=for-the-badge&color=8957E5&label=SYSTEM+VIEWS"/>

</div>

<img src="./assets/divider.svg" width="100%"/>

### `00 // whoami`

```python
from pydantic import BaseModel

class Engineer(BaseModel):
    name: str        = "Selma Koudia"
    role: str        = "AI Engineer · Data Scientist"
    focus: list[str] = ["agentic systems", "NL2SQL on enterprise data",
                        "hybrid GraphRAG", "local LLM inference", "LLM security"]
    principle: str   = "if it isn't traced, validated and evaluated, it isn't in prod"
    open_to: str     = "AI Engineer / Data Scientist roles"

Engineer().model_dump_json(indent=2)  # ✓ validated
```

<img src="./assets/divider.svg" width="100%"/>

<div align="center">

<img src="./assets/stack-orbit.svg" width="100%" alt="Core stack orbit"/>

<br/>

**Orchestration · Structured outputs · Observability**<br/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=7FC8FF" alt="LangGraph"/> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=1FC08A" alt="LangChain"/> <img src="https://img.shields.io/badge/Pydantic_v2-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic v2"/> <img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiIgdmlld0JveD0iMCAwIDUxMiA1MTIiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BCjxwYXRoIGQ9Ik0yNTQuNzUgMzAyLjI1TDI4NS4yNSAzMjYuNzVDMjg1LjI1IDMyNi43NSAzMDguNTg3IDMwOS40MTggMzI1Ljc1IDMwNi44NzVDMzQzLjc1IDMwNC4yMDggMzYyLjk1NCAzMTQuMjQ0IDM4MC43NSAzMjYuMjA4QzQwNy42MjkgMzQ0LjI3OSA0MzAuMjUgMzY3LjIwOCA0MzAuMjUgMzY3LjIwOEw0NTYuNzUgMzQxLjIwOEM0NTYuNzUgMzQxLjIwOCAzODMuNjg2IDI2Mi4wNDcgMzI1Ljc1IDI2OS4yMDhDMjg3Ljc1IDI3My45MDUgMjU0Ljc1IDMwMi4yNSAyNTQuNzUgMzAyLjI1WiIgZmlsbD0iI0ZGNUQ1RiIvPgo8cGF0aCBkPSJNODAuMjUgMTUxLjI4Nkw1NS4yNSAxNzguNzg2QzU1LjI1IDE3OC43ODYgMTI0LjkwMiAyNDMuNzg2IDE3OS43NSAyNDMuNzg2QzIwNC43NSAyNDMuNzg2IDIzOS40MTkgMjI0LjIwMSAyNjkuMjUgMTk4Ljc1N0MyODYuMjUgMTg0LjI1NyAzMDUuMjUgMTY3Ljc4NiAzMjQuMjUgMTY3Ljc4NkMzMzcuMDIxIDE2Ny43ODYgMzUzLjg2NiAxNzQuNTUxIDM2OS43NSAxOTIuMzE2QzM2OS43NSAxOTIuMzE2IDM4MC4wMDMgMTg2LjE2OCAzODYuMjUgMTgxLjc1QzM5MS43NCAxNzcuODY4IDM5OS44OTYgMTcxLjI1IDM5OS44OTYgMTcxLjI1QzM3Ny4wNDcgMTQ2Ljg2NCAzNDMuOTk4IDEyOS4wMzggMzI0LjI1IDEzMC43ODZDMjkyLjI1IDEzMC43OSAyNjkuMjUgMTUwLjcxMSAyNDAuNzUgMTczLjc1QzIxMi4yNSAxOTYuNzg5IDIwMC4yNSAyMDYuMjg2IDE3OS43NSAyMDYuMjg2QzE0NS4yNSAyMDYuMjg2IDgwLjI1IDE1MS4yODYgODAuMjUgMTUxLjI4NloiIGZpbGw9IiM0RTlDRkYiLz4KPHBhdGggZD0iTTgwLjI1IDM2MC43NUw1NS4yNSAzMzMuMjVDNTUuMjUgMzMzLjI1IDEyNC45MDIgMjY4LjI1IDE3OS43NSAyNjguMjVDMjA0Ljc1IDI2OC4yNSAyMzkuNDE5IDI4Ny44MzUgMjY5LjI1IDMxMy4yNzlDMjg2LjI1IDMyNy43NzkgMzA1LjI1IDM0NC4yNSAzMjQuMjUgMzQ0LjI1QzMzNy4wODMgMzQ0LjI1IDM1My43OTkgMzM3LjIwNyAzNjkuNzUgMzE5LjI1QzM2OS43NSAzMTkuMjUgMzc5LjMzOSAzMjUuMTYxIDM4NS4yNSAzMjkuMjVDMzkxLjMyOCAzMzMuNDU1IDQwMC4yNSAzNDAuNDA3IDQwMC4yNSAzNDAuNDA3QzM3Ny4zOSAzNjQuOTg3IDM0NC4xIDM4My4wMDcgMzI0LjI1IDM4MS4yNUMyOTIuMjUgMzgxLjI0NiAyNzMuMjUgMzY0LjI4OSAyNDQuNzUgMzQxLjI1QzIxNi4yNSAzMTguMjExIDIwMC4yNSAzMDUuNzUgMTc5Ljc1IDMwNS43NUMxNDUuMjUgMzA1Ljc1IDgwLjI1IDM2MC43NSA4MC4yNSAzNjAuNzVaIiBmaWxsPSIjNEU5Q0ZGIi8%2BCjxwYXRoIGQ9Ik00MDYuMjUgMjEzLjI1QzM5OS43NDUgMjE3Ljc0NiAzODkuMjUgMjI0LjI1IDM4OS4yNSAyMjQuMjVDMzg5LjI1IDIyNC4yNSAzOTUuMjUgMjM3LjI1IDM5NS4yNSAyNTQuNzVDMzk1LjI1IDI3Mi4yNSAzODkuNzUgMjg3LjI1IDM4OS43NSAyODcuMjVDMzg5Ljc1IDI4Ny4yNSAzOTkuMTcyIDI5My4xMzUgNDA1LjI1IDI5Ny4yNUM0MTEuNTY0IDMwMS41MjUgNDIxLjI1IDMwOC43NSA0MjEuMjUgMzA4Ljc1QzQyMS4yNSAzMDguNzUgNDMyLjc1IDI4NC43NSA0MzIuNzUgMjU0Ljc1QzQzMi43NSAyMjQuNzUgNDIxLjI1IDIwMi4yNSA0MjEuMjUgMjAyLjI1QzQyMS4yNSAyMDIuMjUgNDEyLjIyNiAyMDkuMTIgNDA2LjI1IDIxMy4yNVoiIGZpbGw9IiM0RTlDRkYiLz4KPHBhdGggZD0iTTI1Ni4yNSAyMDkuMjVMMjg1LjI1IDE4NS4yNUMyODUuMjUgMTg1LjI1IDMwOC41ODcgMjAyLjA0IDMyNS43NSAyMDQuNTgzQzM0My43NSAyMDcuMjUgMzYyLjk1NCAxOTcuMjE0IDM4MC43NSAxODUuMjVDNDA3LjYyOSAxNjcuMTc5IDQzMC4yNSAxNDQuMjUgNDMwLjI1IDE0NC4yNUw0NTYuNzUgMTcwLjI1QzQ1Ni43NSAxNzAuMjUgMzgzLjY4NiAyNDkuNDExIDMyNS43NSAyNDIuMjVDMjg3Ljc1IDIzNy41NTMgMjU2LjI1IDIwOS4yNSAyNTYuMjUgMjA5LjI1WiIgZmlsbD0iI0ZGNUQ1RiIvPgo8cGF0aCBkPSJNMTg2LjI1NSAxMzAuMjVDMjIzLjc1NSAxMzAuMjUgMjU1LjI1IDE2Mi4yNSAyNTUuMjUgMTYyLjI1QzI1NS4yNSAxNjIuMjUgMjQ2LjQ4NyAxNjkuMTU1IDI0MC43NSAxNzMuNzVDMjM0Ljc3NSAxNzguNTM2IDIyNS4yNSAxODYuMjUgMjI1LjI1IDE4Ni4yNUMyMjUuMjUgMTg2LjI1IDIwOC43NTUgMTY4Ljc1IDE4Ni4yNTUgMTY4Ljc1QzE3Ny4wMjggMTY4Ljc1IDE2NS4wMzkgMTc0LjI5MiAxNTIuMjU1IDE4NS4yNUMxNDIuMzkxIDE5My43MDUgMTMyLjEyOSAyMDQuMjE2IDEyNS4yNTUgMjE3LjI1QzExOS4zMSAyMjguNTIgMTE2LjA2OCAyNDEuODAyIDExNS43NTUgMjU1Ljc1QzExNS4zNjEgMjczLjI2OSAxMjEuNTcxIDI5MS42MzQgMTMxLjc1NSAzMDYuMjVDMTM4LjU4IDMxNi4wNDYgMTQ2LjcyNiAzMjMuNDE4IDE1NS4yNTUgMzI5Ljc1QzE2Ni4zMjMgMzM3Ljk2OCAxNzcuODY1IDM0My43NSAxODYuMjU1IDM0My43NUMxOTUuMjE3IDM0My43NSAyMDMuMjc0IDM0MC42MzUgMjA5LjI1NSAzMzcuNzVDMjE4Ljc1NSAzMzIuMjUgMjI2LjI1IDMyNS43NSAyMjYuMjUgMzI1Ljc1TDI1NS43NSAzNTAuMjVDMjU1Ljc1IDM1MC4yNSAyNDMuNzUgMzYyLjI1IDIyNy4yNTUgMzcxLjI1QzIxNi41OTUgMzc2LjUwNyAyMDIuODk1IDM4MS43NSAxODYuMjU1IDM4MS43NUMxNjkuNjI2IDM4MS43NSAxNTAuMzE1IDM3Mi45MTUgMTMyLjI1NSAzNTkuMjVDMTIwLjU3OSAzNTAuNDE2IDEwOS4xMzUgMzM5Ljk0OCAxMDAuMjU1IDMyNy4yNUM4NS43MDA1IDMwNi40MzggNzguMjAwNCAyODEuMTE4IDc4LjI1MDIgMjU1Ljc1Qzc4LjMwMDggMjMwLjA2NSA4Ni41ODIzIDIwNC42MjUgMTAxLjI1NSAxODMuNzVDMTI0LjI1NSAxNTMuNzUgMTU4LjI3MyAxMzAuMjUgMTg2LjI1NSAxMzAuMjVaIiBmaWxsPSIjRkY1RDVGIi8%2BCjwvc3ZnPgo%3D" alt="Langfuse"/>

**Inference · Quantization · Deep Learning**<br/>
<img src="https://img.shields.io/badge/vLLM-0F172A?style=for-the-badge&logo=vllm&logoColor=30A2FF" alt="vLLM"/> <img src="https://img.shields.io/badge/%F0%9F%A6%99_llama.cpp-18181B?style=for-the-badge" alt="llama.cpp"/> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000" alt="Hugging Face"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>

**Retrieval · Data · Serving**<br/>
<img src="https://img.shields.io/badge/LightRAG-6D28D9?style=for-the-badge&logo=graphql&logoColor=white" alt="LightRAG"/> <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="FAISS"/> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/sqlglot-0D9488?style=for-the-badge&logo=duckdb&logoColor=white" alt="sqlglot"/> <img src="https://img.shields.io/badge/Dataiku-2AB1AC?style=for-the-badge&logo=dataiku&logoColor=white" alt="Dataiku"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>

</div>

<img src="./assets/divider.svg" width="100%"/>

<div align="center">

<img src="./assets/agent-pipeline.svg" width="100%" alt="Production agentic blueprint"/>

</div>

<details>
<summary><b>▸ how the pipeline works (click)</b></summary>

| Stage | What happens | Tooling |
|---|---|---|
| Guardrails | prompt-injection & PII scan before anything touches a model | custom rules + LLM judge |
| Router | `StateGraph` classifies intent and dispatches to the right sub-graph | LangGraph |
| Retrieval | hybrid graph + vector retrieval over docs and the data catalog | LightRAG · FAISS |
| Text-to-SQL | schema linking → generation → AST validation before execution | sqlglot |
| Validation | every model output is parsed into a typed contract | Pydantic v2 |
| Inference | local, quantized models behind an OpenAI-compatible API | vLLM · llama.cpp |
| Tracing | spans, latency, cost and eval scores on every run | Langfuse |

</details>

<img src="./assets/divider.svg" width="100%"/>

### `03 // DEMO`

https://github.com/user-attachments/assets/dd76f7a0-a053-4cc4-aff0-b654018002b9

<img src="./assets/divider.svg" width="100%"/>

### `04 // FEATURED BUILDS`

<table>
<tr>
<td width="33%" valign="top">

**🧠 NL2SQL Catalog Agent**<br/>
<sub>LangGraph · sqlglot · Pydantic</sub>

Answers questions about tables & columns, writes SQL, validates the AST, explains the result.

<a href="https://github.com/selmakoudia03">→ repo</a>
</td>
<td width="33%" valign="top">

**🕸️ Hybrid GraphRAG**<br/>
<sub>LightRAG · FAISS · local LLM</sub>

Knowledge-graph + vector retrieval for grounded answers over enterprise docs.

<a href="https://github.com/selmakoudia03">→ repo</a>
</td>
<td width="33%" valign="top">

**⚡ Local Inference Lab**<br/>
<sub>vLLM · llama.cpp · Langfuse</sub>

Serving & benchmarking quantized models (AWQ / GGUF) with full tracing.

<a href="https://github.com/selmakoudia03">→ repo</a>
</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

### `05 // TELEMETRY`

<div align="center">

<img src="./profile-3d-contrib/profile-night-rainbow.svg" width="100%" alt="3D contributions"/>

<img src="https://streak-stats.demolab.com?user=selmakoudia03&theme=github-dark-blue&hide_border=true&background=0D1117&ring=A371F7&fire=F778BA&currStreakLabel=58A6FF" width="49%"/>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=selmakoudia03&bg_color=0D1117&color=58A6FF&line=A371F7&point=F778BA&area=true&hide_border=true" width="49%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/selmakoudia03/selmakoudia03/output/github-snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/selmakoudia03/selmakoudia03/output/github-snake.svg" width="100%" alt="snake"/>
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8957E5,50:1F6FEB,100:0D1117&height=110&section=footer&text=trace%20everything%20·%20validate%20everything&fontSize=18&fontColor=C9D1D9&fontAlignY=70" width="100%"/>
