# Sukhman Singh

I work on AI agent infrastructure and the backend systems underneath it — coordination, auth, and the plumbing that makes multi-agent systems behave.

- 🔭 Working on agent infrastructure, mostly in Python and Go
- ✍️ I write at [Sukhman's Blog](https://sukhman31.github.io/blog/)
- 📫 Reach me at labana.sukhman@gmail.com

## Experience

Software engineer on a platform team, building the infrastructure underneath a large internal API ecosystem:

- API schema governance and proto-to-artifact publishing pipelines across 1,600+ internal APIs serving over a billion requests a year
- OAuth 2.0 and OPA-based runtime authorization, mutual TLS, and a zero-trust ABAC entitlement system enforcing thousands of policies across hundreds of servers
- Real-time event delivery on Kafka Streams, at a scale of tens of billions of events a year
- Developer tooling, including a Go CLI adopted by 1,300+ engineers

Before that, an AI/LLM internship at a YC-backed startup: a production OCR microservice on FastAPI, and an LLM agent framework with task-specific routing and eval pipelines.

## Selected projects

| Project | What it is |
| --- | --- |
| [agentkeeper](https://github.com/sukhman31/agentkeeper) | gRPC coordination daemon for multi-agent AI systems: task assignment, leader election, ABAC entitlements and crash recovery, shipped as a zero-dependency Go binary with a Python SDK |
| [PieceByPiece](https://tokenizer-frontend.fly.dev) | Full-stack platform for training custom BPE and WordPiece tokenizers on your own corpora, with live job status streamed from a Python gRPC backend to a React frontend through a Go gateway |
| [agent-auth](https://github.com/sukhman31/auth0-agent) | A self-hostable OAuth2/OIDC authorization server for AI agent applications, with four grant types and JWKS verification |
| [jax-train](https://github.com/sukhman31/jax-train) | Building a modern LLM from scratch in JAX and Flax NNX, through to running real inference |

## Tech

- **ML / AI** — PyTorch, HuggingFace Transformers, JAX and Flax, ONNX, LLM agent frameworks, eval pipelines, multi-agent coordination
- **Languages** — Python, Go, Java
- **Infrastructure** — gRPC, Protocol Buffers, Kafka, Kubernetes, Docker, OAuth 2.0, OPA and ABAC, Azure, Prometheus and Grafana

<!---
sukhman31/sukhman31 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
