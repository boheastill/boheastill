# Bohea Still

**I build the software that ships with machines: everything between "the machine arrived" and "your customer's people run it every day". Proof before promises.**

I take ambiguous, high-risk work from a working prototype to measured delivery and handover, and I show you something running before you commit.

Backend work in Java and Go from 2019 to 2026 came before industrial Python, so **I speak ERP as fluently as Modbus.**

The repositories below include open-source tools, independent benchmarks, credential-free demos and production-derived work. Client work is anonymized where contracts or NDAs require it, and each public demo states what was measured, which data is synthetic, and what the result does and doesn't prove.

## What I solve

1. **Software that ships with a machine.** Operator HMIs, device integration over Modbus, OPC UA and MQTT, and machine data sent upstream into an ERP. One interface across every model you ship, instead of a different one per machine.
2. **Systems that don't talk.** The count your line reports doesn't match the count your ERP received, and someone spends days each month finding out why. Integrations, protocol bridges and reconciliation.
3. **Software an AI wrote that won't run.** A prototype that demos well but that nobody can deploy, extend or debug. I take it over and make it survive production.

**For hire.** [boheastill.com](https://boheastill.com/?r=gh-profile): fixed scope, milestone payments, and you own the source outright. Client projects run on servers in the US, and client data stays there.

## Production experience

| Work | What shipped |
|---|---|
| [Inside a robot manufacturer](https://boheastill.com/cases/inside-a-robot-maker/?r=gh-profile) | Sole developer for every internal system at **Standard Robots**, a Shenzhen AMR maker, for nearly two years: BOM and supply chain, CRM, deployment, and a binlog recovery that got back 100% of deleted data. Not their fleet software, and the page says so. A signed letter from the CTO is available on request. |
| [High-concurrency backends](https://boheastill.com/?r=gh-profile) | Event-driven ERP/WMS with downtime failures down about 90%, throughput taken from 50 to 5,000+ QPS, and a production database migration across seven microservices. |
| [Voice AI pipeline](https://byteplain.com/projects/voice-ai-pipeline/?r=gh-profile) | A production donation-call pipeline: phone call to transcription to a structured spreadsheet row in about 16 seconds. |

## Public, runnable proof

| Project | Evidence type | Measured result |
|---|---|---|
| [ClickHouse DWH tuning](https://github.com/boheastill/clickhouse-dwh-tuning-demo) | Controlled 50M-row benchmark | A filtered query scans about 230× less data. One-command reproducible and CI-guarded. |
| [MQTT machine safety gates](https://github.com/boheastill/mqtt-machine-safety-gates) | Adversarial acceptance harness | 11 checks: nine attempts to make a machine misbehave, all refused or safe-stopped, and two that confirm it can still stop and recover. Enforced in CI. |
| [LLM agent payment gates](https://github.com/boheastill/llm-agent-payment-gates) | Adversarial attack harness | Fifteen attempts to move money that shouldn't move, all of which fail. Three were added after a reviewer broke an earlier version. |
| [Sparkplug B host](https://github.com/boheastill/sparkplug-host) | Spec-conformance scenarios | Fourteen situations that break naive hosts, including stale death certificates, sequence gaps and unknown aliases. No maintained open-source Python host existed. |
| [RealSense D405 depth toolkit](https://github.com/boheastill/rs-d405-depth-toolkit) | Hardware-facing synthetic benchmark | Filter and fusion pipeline with a quantitative accuracy-validation harness, ready for real `.bag` recordings. |
| [Regulatory document parser](https://github.com/boheastill/gov-doc-parser-framework) | Public-source validation | A 233-article statute parsed into strictly validated JSON with zero warnings. |
| [District-aware route optimizer](https://github.com/boheastill/montreal-district-vrp-solver) | Synthetic routing scenario | 218 km down to 175 km on identical stops, with every mandatory stop honored. |
| [German number ASR](https://github.com/boheastill/german-number-asr-demo) | Synthetic speech and noise benchmark | Constrained decoding reaches 52% vs 14% at 5 dB, with the test limits documented. |

Case studies, walkthroughs and working terms: **[boheastill.com](https://boheastill.com/?r=gh-profile)**

## Open source

- [**Intranet-Chat-Stream**](https://github.com/boheastill/Intranet-Chat-Stream): a self-hosted, database-free stream for moving text and files between your PC, phone and AI agents. One Go binary, bilingual UI, CI and releases.
- [**hua-mcp**](https://github.com/boheastill/hua-mcp): a fleet of MCP servers with no central registry, one directory and one port per MCP, discovered by scanning. Documents the three root causes that took servers down in production.
- [**pdfSplit**](https://github.com/boheastill/pdfSplit): bounded parallel PDF rendering, about 1,000 pages in 2.5 minutes instead of 50.
- [**qoder-nix**](https://github.com/boheastill/qoder-nix): run Qoder IDE on NixOS with one command.

## Contact

📫 [hi@boheastill.com](mailto:hi@boheastill.com) · 🌐 [boheastill.com](https://boheastill.com/?r=gh-profile) · 中文 → [boheastill.com/zh/](https://boheastill.com/zh/?r=gh-profile)

Alongside the practice I keep a non-commercial lab, [byteplain.com](https://byteplain.com/?r=gh-profile), where I take new technology apart and explain it in plain language. One full industrial practice plus a research habit, not two half-time jobs: client work always comes first.
