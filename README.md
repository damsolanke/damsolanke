### Dam Solanke

AI architect and platform engineer with 20 years building large-scale distributed systems, including healthcare platforms. My current work is agentic AI and the evaluation around it: tool-calling agents with a critic pass, retrieval that cites its sources, and checking whether a result still holds when it is rerun.

**Selected projects**

| Project | Stack | What it does |
|---------|-------|-------------|
| [**aarogya-atlas**](https://github.com/damsolanke/aarogya-atlas) | TypeScript, Python, FHIR, LLM tool calling | Hack-Nation 2026 project. Tool-calling loop over 12 typed tools with a critic pass over FHIR-aligned data; answers cite source facility ids. The hosted version uses cloud inference; an optional on-device mode runs photo triage and embeddings on local models. [Live demo](https://aarogya-atlas.vercel.app) |
| [**gemma4-swe-kit**](https://github.com/damsolanke/gemma4-swe-kit) | Python, vLLM, MLX, LoRA | Local tools that reproduce the Kaggle Gemma 4 Developer Agent scorer, so prompts and tool-call parsing can be tested before a submission. Its parser matches vLLM's on 59,926 of 60,000 random inputs (vLLM's own parser hangs on the other 74); rewriting the shell examples in the prompt cut malformed tool names from 31% to 5% on replayed failures; curation kept 1,427 of 3,567 agent trajectories for distillation. |
| [**arc-prize-2026**](https://github.com/damsolanke/arc-prize-2026) | PyTorch, Qwen3, LoRA, test-time training | NVARC-style ARC-AGI-2 system and a study of leaderboard rerun noise: identical reruns vary with a pooled SD of 1.35 points, enough to overturn a ranking built on one run per configuration. Best public score 31.39. |
| [**gcp-financial-data-platform**](https://github.com/damsolanke/gcp-financial-data-platform) | Go, Airflow, dbt, BigQuery, Terraform | Reference architecture for financial data infrastructure: event ingestion, batch transforms, governed access and cross-region backups, with the infrastructure as Terraform modules |
| [**geochemical-dating**](https://github.com/damsolanke/geochemical-dating) | XGBoost, LightGBM, scikit-learn | **2nd place on Kaggle.** Two-branch ensemble for 3-class geological age classification, private Macro-F1 0.96988, 0.00104 behind first |
| [**nci-data-reuse-ledger**](https://github.com/damsolanke/nci-data-reuse-ledger) | Python, dbGaP, Europe PMC, iCite | Links a sample of approved dbGaP access requests for NCI datasets (TCGA, CPTAC) to the papers that followed: who reuses NCI data, how fast, and from which kinds of institution. Proof of concept for the NCI ODS Data Sharing Impact Prize. |
| [**winding-model-eval**](https://github.com/damsolanke/winding-model-eval) · [**sheet-tracer-eval**](https://github.com/damsolanke/sheet-tracer-eval) | PyTorch, CT volumes | Held-out evaluations of two published Vesuvius Challenge models, scored with the challenge's own benchmark and metric code |

**Current work (2026; code stays private while each challenge runs)**

- **Kaggle Gemma 4 Developer Agent:** a coding agent for the competition's Gemma 4 31B harness (ADK on vLLM), tested with gemma4-swe-kit, and two write-ups submitted to the Paper Track in October.
- **NLM SPARK challenge:** four offline systems over PubMed and dbGaP, from finding the paper a question describes to writing answers that cite the abstracts behind each sentence. Each runs from its own Docker image with open-weight models.
- **IEEE CIS challenge on domain-specific question answering with LLMs:** retrieval and answering over a corpus of real and distractor PDFs.
- **NIH "It's About Time" challenge:** TKG-PV, a bitemporal, evidence-aware ontology for temporal reasoning in pharmacovigilance knowledge graphs, submitted to Phase 1. It will be published in the [tkgpv](https://github.com/damsolanke/tkgpv) repo after Phase 1 closes on 15 January 2027.
- **ARC Prize 2026 Paper Track:** a paper on rerun noise and contaminated dev checks in an NVARC-style system.

**Stack**

Python, Go, SQL, TypeScript · LLM agents (ADK, tool calling), RAG, evals and tracing (MLflow) · vLLM, Ollama, MLX, LoRA fine-tuning · PyTorch, XGBoost, LightGBM · AWS and GCP · Kubernetes, Terraform, Airflow, dbt, BigQuery, Pub/Sub, PostgreSQL, pgvector · FHIR-aligned data models

Dallas-Fort Worth, TX
