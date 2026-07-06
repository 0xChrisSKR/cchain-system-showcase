# C-Chain System Showcase

[![CI](https://github.com/0xChrisSKR/cchain-system-showcase/actions/workflows/ci.yml/badge.svg)](https://github.com/0xChrisSKR/cchain-system-showcase/actions/workflows/ci.yml)

[![Portfolio](https://img.shields.io/badge/Portfolio-Chris%20Chuang-0f172a?style=flat-square)](https://github.com/0xChrisSKR)
![Status](https://img.shields.io/badge/Status-Public%20Architecture-7c3aed?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Blockchain%20Infrastructure-2563eb?style=flat-square)
![Claims](https://img.shields.io/badge/Claims-Verifiable%20Only-16a34a?style=flat-square)

![C-Chain architecture](assets/architecture.png)

C-Chain is my AI-oriented blockchain infrastructure prototype, designed as the underlying infrastructure direction for later TRACE work.

This repository explains the architecture and product evolution without exposing private source code, private network topology, deployment details, private RPC endpoints, or secrets.

## One-line Positioning

Private / experimental blockchain infrastructure prototype connecting Web3 transaction safety, proof / receipt concepts, and AI platform evolution.

## Problem

Web3 and AI-assisted product interfaces need clear transaction preparation, signing boundaries, status, finality, receipt, and verification. Without those boundaries, users can be misled by unclear state or unsafe action flows.

## My Role

I planned and designed the infrastructure direction, wallet boundary model, transaction preparation flow, proof / receipt concepts, RPC gateway direction, node topology concepts, and public showcase package.

## What I Designed

- Private PoA chain planning.
- Node deployment direction.
- RPC gateway concept.
- Proof / Receipt concepts.
- State handling.
- WireGuard private network topology concept.
- Explorer and health check direction.
- Evolution path from WorldPeace DAO and C-Wallet toward TRACE ProofFeed and TRACE AI Platform.

## Tech Stack

- Private PoA chain architecture
- RPC gateway concepts
- Explorer and health checks
- WireGuard topology planning
- Proof / Receipt design
- Wallet and transaction boundary design
- Web3 infrastructure


## Engineering Assets

![System overview](assets/system-overview.png)

![Architecture](assets/architecture.png)

![Runtime](assets/runtime.png)

![Deployment](assets/deployment.png)

- CI workflow: [.github/workflows/ci.yml](.github/workflows/ci.yml)
- Deployment preview: [Dockerfile](Dockerfile), [docker-compose.yml](docker-compose.yml), [.env.example](.env.example)
- API examples: [docs/API_EXAMPLES.md](docs/API_EXAMPLES.md)
- Folder structure: [docs/FOLDER_STRUCTURE.md](docs/FOLDER_STRUCTURE.md)
- Engineering notes: [docs/ENGINEERING_NOTES.md](docs/ENGINEERING_NOTES.md)
- Performance notes: [docs/PERFORMANCE.md](docs/PERFORMANCE.md)
- Security notes: [docs/SECURITY.md](docs/SECURITY.md)
- Future work: [docs/FUTURE_WORK.md](docs/FUTURE_WORK.md)
- Reviewer notes: [docs/CAREER_MAPPING.md](docs/CAREER_MAPPING.md)

## Local Deployment Preview

```bash
cp .env.example .env
docker compose up --build
```

Open `http://localhost:8080` after the container starts. This preview serves the public showcase package only.

The deployment preview is for repository review and portfolio evaluation. It does not expose private infrastructure, secrets, production topology, or private source code.

## Public Artifacts

- Architecture: [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md)
- Public artifacts: [docs/PUBLIC_ARTIFACTS.md](docs/PUBLIC_ARTIFACTS.md)
- Visual artifacts: [docs/SCREENSHOTS.md](docs/SCREENSHOTS.md)
- Lessons learned: [docs/LESSONS_LEARNED.md](docs/LESSONS_LEARNED.md)
- 104 summary: [docs/104_PROJECT_SUMMARY.md](docs/104_PROJECT_SUMMARY.md)
- What this proves: [docs/WHAT_THIS_PROVES.md](docs/WHAT_THIS_PROVES.md)
- What this does not claim: [docs/WHAT_THIS_DOES_NOT_CLAIM.md](docs/WHAT_THIS_DOES_NOT_CLAIM.md)

## Screenshots / Diagrams

- Architecture diagram: `assets/architecture.png`
- Mermaid source: `assets/diagrams/architecture.mmd`

No product UI screenshot is claimed for this repository; it is presented as an architecture and infrastructure showcase.

## Relation to the Portfolio Narrative

C-Chain connects the early Web3 product lineage with later verification and AI platform work: WorldPeace DAO -> C-Chain Infrastructure -> Immune RPC Gate -> TRACE ProofFeed -> TRACE AI Platform.

## Related Projects

- WorldPeace DAO: https://github.com/0xChrisSKR/worldpeace-dao-showcase
- Immune RPC Gate: https://github.com/0xChrisSKR/immune-rpc-gate
- TRACE ProofFeed: https://github.com/TRACE-CChain-Labs/trace-prooffeed-solana-agent

## What A Reviewer Can Verify

- The wallet and signing boundary model.
- The architecture diagram and Mermaid source.
- The proof / receipt direction.
- The claim boundary: private / experimental infrastructure, not public mainnet adoption.

## Status Note

C-Chain is private / experimental infrastructure. I do not present it as a public mainnet, a production blockchain, or a system with user adoption.
