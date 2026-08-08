# Bohea Still

**Independent engineer for industrial integration, data/backend systems, and practical AI automation.**

I take ambiguous, high-risk work from a working prototype to measured delivery and handover. **Proof before promises — working demos before contracts.**

Public repositories below include open-source tools, independent benchmarks, credential-free demos, and production-derived work. Client work is anonymized where contracts or NDAs require it; each public demo states what was measured, what data is synthetic, and what the result does — and does not — prove.

## What I solve

1. **Software that ships with a machine** — operator HMIs, device integration over Modbus/OPC UA/MQTT, and getting machine data upstream into an ERP. One interface across every model you ship, not a different one per machine.
2. **Systems that don't talk** — the count your line reports and the count your ERP received don't match, and someone spends days each month finding out why. Integrations, protocol bridges and reconciliation.
3. **Software an AI wrote that won't run** — a prototype that demos beautifully and cannot be deployed, extended or debugged by anyone. I take it over and make it survive production.

## Production experience

| Work | What shipped |
|---|---|
| [Inside a robot manufacturer](https://boheastill.com/cases/robotics-hmi?r=gh-profile) | Sole developer for every internal system at **Standard Robots**, a Shenzhen AMR maker: BOM and supply chain, CRM, deployment, a 100% binlog data recovery. Not their fleet software — I say so on the page. The CTO signed a letter; it is published in full. |
| [High-concurrency backends](https://boheastill.com/?r=gh-profile) | Event-driven ERP/WMS, downtime failures reduced by ~90%, throughput taken from 50 to 5,000+ QPS, and a production database migration across seven microservices. |
| [Voice AI pipeline](https://boheastill.com/cases/voice-ai-pipeline?r=gh-profile) | A production donation-call pipeline: phone call → transcription → structured spreadsheet row in about 16 seconds, end to end. |

## Public, runnable proof

| Project | Evidence type | Measured result |
|---|---|---|
| [ClickHouse DWH tuning](https://github.com/boheastill/clickhouse-dwh-tuning-demo) | Controlled 50M-row benchmark | A filtered query scans ~230× less data; the result is one-command reproducible and CI-guarded. |
| [RealSense D405 depth toolkit](https://github.com/boheastill/rs-d405-depth-toolkit) | Hardware-facing synthetic benchmark | Filter/fusion pipeline with a quantitative accuracy-validation harness, ready for real `.bag` recordings. |
| [Regulatory document parser](https://github.com/boheastill/gov-doc-parser-framework) | Public-source validation | 233-article statute → strictly validated JSON with 0 warnings. |
| [District-aware route optimizer](https://github.com/boheastill/montreal-district-vrp-solver) | Synthetic routing scenario | 218 → 175 km on identical stops while honoring every mandatory stop. |
| [German number ASR](https://github.com/boheastill/german-number-asr-demo) | Synthetic speech/noise benchmark | Constrained decoding reaches 52% vs 14% at 5 dB, with the test limits documented. |
| [MQTT machine safety gates](https://github.com/boheastill/mqtt-machine-safety-gates) | Adversarial acceptance harness | Eleven attempts to make a machine misbehave; all refused or safe-stopped, enforced in CI. |
| [LLM agent payment gates](https://github.com/boheastill/llm-agent-payment-gates) | Adversarial attack harness | Fifteen attempts to move money that shouldn't move; all fail. Three were added after a reviewer broke an earlier version. |
| [Sparkplug B host](https://github.com/boheastill/sparkplug-host) | Spec-conformance scenarios | Fourteen situations that break naive hosts — stale death certificates, sequence gaps, unknown aliases. No maintained open-source Python host existed. |

Full case studies, walkthroughs and working terms: **[boheastill.com](https://boheastill.com/?r=gh-profile)**

## Open source

- [**Intranet-Chat-Stream**](https://github.com/boheastill/Intranet-Chat-Stream) — a self-hosted, DB-less stream for moving text and files between your PC, phone and AI agents. One Go binary, bilingual UI, CI and releases.
- [**qoder-nix**](https://github.com/boheastill/qoder-nix) — run Qoder IDE on NixOS with one command.
- [**pdfSplit**](https://github.com/boheastill/pdfSplit) — bounded parallel PDF rendering: roughly 1,000 pages from 50 minutes to 2.5 minutes.
- [**hua-mcp**](https://github.com/boheastill/hua-mcp) — a fleet of MCP servers with no central registry: one MCP = one directory = one port, discovered by scanning. Documents the three root causes that actually killed servers in production.

## Contact

📫 [hi@boheastill.com](mailto:hi@boheastill.com) · 🌐 [boheastill.com](https://boheastill.com/?r=gh-profile) · 中文 → [boheastill.com/?lang=zh](https://boheastill.com/?lang=zh&r=gh-profile)
