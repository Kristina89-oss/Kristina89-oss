<div align="center">

<img src="assets/hero.gif" width="180" alt="rotating icosahedron" />

# AI Automation Engineer
### LLM agents · Workflow automation · Evals · GTM & marketing ops

[![Taplink](https://img.shields.io/badge/Taplink-Phenomenon-000000?style=flat-square)](https://taplink.cc/gipoteza_nule)
[![Research](https://img.shields.io/badge/Research-LLM%20introspection-334155?style=flat-square)](https://github.com/Kristina89-oss/llm-introspection-experiments)
[![Data](https://img.shields.io/badge/Zenodo-10.5281%2Fzenodo.23365351-334155?style=flat-square)](https://doi.org/10.5281/zenodo.23365351)

</div>

---

## What I do

I build automations where an LLM does real work inside a business process — pulling data from APIs, analysing it, and handing a person a decision instead of a spreadsheet. I came from performance marketing, so I start from the process and the metric, not from the model: what has to happen, how we will know it worked, and what it costs per run.

The other half of my work is checking whether a model actually does what it seems to do. I ran 15 controlled experiments on Claude and Qwen models — hundreds of sub-agent instances, pre-registered comparisons, blind LLM-as-judge coding, LoRA fine-tuning — and published the data and code. That habit carries over to every agent I build: evals first, demos second.

---

## 🧪 Featured: LLM introspection experiments

**[llm-introspection-experiments →](https://github.com/Kristina89-oss/llm-introspection-experiments)**

Can a language model report on its own internal states — and does it have a past of its own? Nine studies and a pre-registered replication series, run with Claude Code as the orchestration layer.

| | |
|---|---|
| **Scale** | 785 Claude instances (Opus 5 / 5.5, Haiku 4.5) + 38 blind coders; Qwen2.5-1.5B/3B fine-tuned on a 4 GB laptop GPU |
| **Method** | Isolated sub-agents per condition, pre-registration, two blind LLM coders (κ 0.71–1.0), Wilson/Newcombe CIs, Holm correction |
| **Finding** | Introspection exists only *within a single computation*; between turns the model reads its own past like an outsider — **the past is public** |
| **Honesty** | One headline effect did not survive replication (it was word order in the prompt) — reported as such |

📄 [Article](https://github.com/Kristina89-oss/llm-introspection-experiments/blob/main/article.md) · 🧪 [All studies](https://github.com/Kristina89-oss/llm-introspection-experiments/blob/main/experiments.md) · 📚 [191 sources](https://github.com/Kristina89-oss/llm-introspection-experiments/blob/main/sources.md) · 🌐 [Notion companion](https://experienced-hygienic-9aa.notion.site/Consciousness-and-AI-Experiments-Sources-and-Notes-3f2e2190382d81709bf3ef6fe4d0ade4) · 💾 [Data & code (Zenodo)](https://doi.org/10.5281/zenodo.23365351)

---

## ⚙️ Automation work

| Project | What it does | Stack |
|---|---|---|
| **Ad analytics pipeline** | Pulls campaign stats from the Yandex Direct API, lands them in Google Sheets, and has a low-cost LLM write the daily analysis: what moved, why, what to change | n8n · Yandex Direct API · Google Sheets · Gemini |
| **Telegram budget bot** | Watches ad spend and sends budget alerts and summaries to Telegram | n8n · Telegram Bot API |
| **Local LLM parsing** | Turns unstructured text into structured fields with a local model, so data never leaves the machine | n8n · Ollama |
| **Research orchestration** | Runs hundreds of isolated model instances per experiment, blind-codes answers with LLM judges, recomputes every statistic from raw counts | Claude Code · Python · PyTorch · PEFT/LoRA |

### 🚧 Building now

- **Ad-Ops agent** — a production agent on Yandex Direct: tool use, guardrails, logging, cost per run
- **RAG + eval harness** — retrieval over marketing docs with hybrid search, reranking and an automatic eval set
- **GTM engine** — lead qualification bot (BANT), CRM sync, ICP scoring
- **MCP server for Yandex Direct** — so any agent can read and manage campaigns, with trajectory evals

---

## 🧭 Core skills

| Area | Skills |
|---|---|
| Agents & LLM apps | Tool use / function calling · ReAct · Model routing · Prompt design · MCP |
| Retrieval | RAG · Chunking · Hybrid search · Rerankers · GraphRAG |
| Evaluation | LLM-as-judge · Blind double coding · Pre-registration · Confidence intervals · Tracing |
| Automation | n8n · REST APIs · Webhooks · Google Sheets · Telegram bots |
| Models | Claude · Gemini · Ollama · Qwen fine-tuning (LoRA / QLoRA) |
| Domain | Performance marketing · Ad ops · GTM |

---

## 🛠️ Tools

![n8n](https://img.shields.io/badge/n8n-334155?style=flat-square)
![Claude](https://img.shields.io/badge/Claude%20Code-334155?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-334155?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-334155?style=flat-square)
![Python](https://img.shields.io/badge/Python-334155?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-334155?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-334155?style=flat-square)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-334155?style=flat-square)
![Telegram](https://img.shields.io/badge/Telegram%20Bot%20API-334155?style=flat-square)
![Notion](https://img.shields.io/badge/Notion-334155?style=flat-square)

---

<details>
<summary>🗂️ Side projects — open-source research I do for fun</summary>

<br>

| Database | Covers |
|---|---|
| **[Arms trafficking: Türkiye → Europe](https://github.com/Kristina89-oss/Arms-trafficking-Turkiye-Europe)** | Turkish blank-firing pistols smuggled into Europe and converted to live weapons |
| **[Crime Networks Database](https://github.com/Kristina89-oss/Crime-networks-Database)** | Scandinavian and Turkish-origin organised crime groups, source-tagged |
| **[China–DRC Database](https://github.com/Kristina89-oss/China-DRC-Database)** | China's mining, cobalt, corruption and security footprint in the DRC |

</details>
