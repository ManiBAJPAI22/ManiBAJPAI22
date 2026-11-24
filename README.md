## Mani Bajpai

Backend engineer. I work on the parts of a system that are expensive to get wrong — payments, settlement, and the webhooks, queues and database transactions underneath them. Most of my time goes to the reliability layer people tend to skip: idempotency, row locking, retries with dead-lettering, reconciliation, and the race conditions that only surface in production.

Currently building payments and settlement at **WeSee** (Node.js, TypeScript, PostgreSQL); previously **GlueX Protocol**. In open source I go looking for the bugs that actually bite — most recently a run of reliability and security fixes across **vLLM's AIBrix** control plane.

<p>
  <a href="https://www.linkedin.com/in/manibajpai/">LinkedIn</a>&nbsp; &middot; &nbsp;<a href="https://x.com/mBinCrypto">X / Twitter</a>&nbsp; &middot; &nbsp;<a href="mailto:manicode22@gmail.com">Email</a>
</p>

### Open source

| Project | Contribution | Status |
| --- | --- | --- |
| `vllm-project/aibrix` | [#3540](https://github.com/vllm-project/aibrix/pull/3540) — register a webhook only when its API group is in the scheme | ![](https://img.shields.io/github/pulls/detail/state/vllm-project/aibrix/3540?style=flat-square&label=) |
| `vllm-project/aibrix` | [#3570](https://github.com/vllm-project/aibrix/pull/3570) — resolve webhook objects for a prefixed install | ![](https://img.shields.io/github/pulls/detail/state/vllm-project/aibrix/3570?style=flat-square&label=) |
| `vllm-project/aibrix` | [#3578](https://github.com/vllm-project/aibrix/pull/3578) — keep a rollout's drains within `maxUnavailable` | ![](https://img.shields.io/github/pulls/detail/state/vllm-project/aibrix/3578?style=flat-square&label=) |
| `vllm-project/aibrix` | [#3579](https://github.com/vllm-project/aibrix/pull/3579) — cancel a rollout drain when the template is reverted | ![](https://img.shields.io/github/pulls/detail/state/vllm-project/aibrix/3579?style=flat-square&label=) |
| `vllm-project/aibrix` | [Reported 8 bugs](https://github.com/vllm-project/aibrix/issues?q=author%3AManiBAJPAI22) — gateway memory DoS, SSRF, autoscaler starvation, rollout drain, standalone-overlay crashes | ![](https://img.shields.io/badge/reported-8-informational?style=flat-square) |
| `kleros/kleros-v2` | [#2104](https://github.com/kleros/kleros-v2/pull/2104) — loading and error states, hardened price fetch | ![](https://img.shields.io/github/pulls/detail/state/kleros/kleros-v2/2104?style=flat-square&label=) |

### Selected projects

| Project | Description | Stack |
| --- | --- | --- |
| [degenOS](https://github.com/ManiBAJPAI22/degenOS) | Winner, ETHGlobal Bangkok | TypeScript |
| [vertigo](https://github.com/PrathmeshRanjan/vertigo) | On-chain prediction-market engine — LOPMM pricing across Uniswap v4 and 1inch venues | TypeScript, Solidity |
| [sift-cli](https://github.com/ManiBAJPAI22/sift-cli) | One-command Solidity audit pipeline (Slither, Aderyn, fuzzing) with LLM triage to cut false positives | Python |
| [ZK-match](https://github.com/ManiBAJPAI22/ZK-match) | Privacy-preserving biometric matching using zero-knowledge proofs | JavaScript |
| [Cross-Chain-Aggregator](https://github.com/ManiBAJPAI22/Cross-Chain-Aggregator) | Cross-chain DeFi routing across Optimism and Osmosis via Axelar | JavaScript |
| [SSM](https://github.com/ManiBAJPAI22/SSM) | Multimodal model training with ONNX export and gRPC serving | Go |

### Tech

**Languages** — TypeScript, JavaScript, SQL, Go, Python, Rust, Solidity
**Backend & data** — Node.js (Express, Fastify, NestJS), PostgreSQL, Redis, TypeORM, BullMQ
**Cloud & infra** — AWS, Docker, Kubernetes, Prometheus

### Activity

<p align="center">
  <img src="./github-metrics.svg" alt="GitHub metrics"/>
</p>
