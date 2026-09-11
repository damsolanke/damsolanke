### Dam Solanke

AI platform engineer with 20 years building large-scale distributed systems. Currently focused on the infrastructure other engineers use to ship AI agents: agent SDKs, MCP tool integration, model gateways, and the evaluation stack that tells you whether an agent actually works.

**Selected projects**

| Project | Stack | What it does |
|---------|-------|-------------|
| [**agent-runtime**](https://github.com/damsolanke/agent-runtime) | Python, pydantic, MCP, OpenAI-compatible APIs | The agent loop from aarogya-atlas, extracted and generalised: typed tools validated before dispatch, a bounded loop with a recovery ladder and JSONL traces, a critic that never fakes a score, the same registry served over MCP, and an eval harness whose scripted cases gate CI at 100% |
| [**aarogya-atlas**](https://github.com/damsolanke/aarogya-atlas) | TypeScript, Python, FHIR, LLM tool calling | Tool-calling loop over 12 typed tools with a critic pass, FHIR-native data, every answer traced to a source record; cloud inference in the hosted demo, on-device mode with a local model. [Live demo](https://aarogya-atlas.vercel.app) |
| [**gcp-financial-data-platform**](https://github.com/damsolanke/gcp-financial-data-platform) | Go, Airflow, dbt, BigQuery, Terraform | Reference architecture for financial data infrastructure — event ingestion, batch transforms, governed access, cross-region backups, all in Terraform |
| [**geochemical-dating**](https://github.com/damsolanke/geochemical-dating) | XGBoost, LightGBM, scikit-learn | **2nd of 31 on Kaggle.** Two-branch ensemble for 3-class geological age classification, private Macro-F1 0.96988 — finished 0.00104 behind first and generalised upward on the private split |

**Competitions**

ARC Prize 2026 (Paper Track) · AI Agent Security: Multi-Step Tool Attacks (OpenAI) · BirdCLEF+ 2026 · AI Mathematical Olympiad Progress Prize 3 · NFL Big Data Bowl 2026 · Gemma 4 Good Hackathon · Hack-Nation 2026 · Orbit Wars

**Stack**

Python, Go, SQL, TypeScript · agent SDKs, MCP, tool calling, evals and tracing · PyTorch, XGBoost, LightGBM · AWS and GCP · Kubernetes, Terraform, Airflow, dbt, BigQuery, Pub/Sub, Kafka, PostgreSQL

MSc Artificial Intelligence · Dallas-Fort Worth, TX
