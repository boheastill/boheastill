# Bohea Still

**Independent engineer for industrial integration, data/backend systems, and practical AI automation.**

I take ambiguous, high-risk work from a working prototype to measured delivery and handover. **Proof before promises — working demos before contracts.**

Public repositories below include open-source tools, independent benchmarks, credential-free demos, and production-derived work. Client work is anonymized where contracts or NDAs require it; each public demo states what was measured, what data is synthetic, and what the result does — and does not — prove.

## What I solve

1. **Software ↔ Hardware** — operator HMIs, fleet scheduling and integration that make industrial robots and devices usable by the people on the floor, not just engineers.
2. **Systems that don't talk** — integrations, RPA and MCP servers that connect the marketing, CRM, e-commerce and payment tools a business already uses.
3. **AI for traditional business** — voice and document pipelines aimed at real operational leaks: missed calls, missed customers and repetitive copy-paste work.

## Production experience

| Work | What shipped |
|---|---|
| [Industrial robotics & HMI](https://boheastill.com/cases/robotics-hmi?r=gh-profile) | Operator interfaces, fleet scheduling and Modbus/TCP integration at a leading AMR manufacturer. Backed by a formal CTO recommendation. |
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

Full case studies, walkthroughs and working terms: **[boheastill.com](https://boheastill.com/?r=gh-profile)**

## Open source

- [**Intranet-Chat-Stream**](https://github.com/boheastill/Intranet-Chat-Stream) — a self-hosted, DB-less stream for moving text and files between your PC, phone and AI agents. One Go binary, bilingual UI, CI and releases.
- [**qoder-nix**](https://github.com/boheastill/qoder-nix) — run Qoder IDE on NixOS with one command.
- [**pdfSplit**](https://github.com/boheastill/pdfSplit) — bounded parallel PDF rendering: roughly 1,000 pages from 50 minutes to 2.5 minutes.

## Contact

📫 [hi@boheastill.com](mailto:hi@boheastill.com) · 🌐 [boheastill.com](https://boheastill.com/?r=gh-profile) · 中文 → [boheastill.com/?lang=zh](https://boheastill.com/?lang=zh&r=gh-profile)
