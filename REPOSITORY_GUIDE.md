# Repository Guide

This guide explains how to read the repositories on this account without confusing current engineering work, public documentation, assessment evidence, and historical artifacts.

## Maturity labels

| Label | Meaning |
|---|---|
| **Active / canonical** | Current source of truth for its documented responsibility |
| **Active documentation** | Public architecture or portfolio material; not a production implementation |
| **Pre-production** | Engineering work that still requires documented validation before production claims |
| **Historical / archived** | Retained for provenance; no longer an active product direction |
| **Private / safety review** | Kept non-public while credentials, history, client data, or release suitability are reviewed |

## Active public work

| Repository | Role | Current maturity |
|---|---|---|
| [project-synapse](https://github.com/Muath-Yousef/project-synapse) | Public architecture, principles, boundaries, and roadmap behind SOCRoot | Active documentation |
| [ide-agentic-engine](https://github.com/Muath-Yousef/ide-agentic-engine) | SOCRoot control plane: portals, RBAC, client state, evidence workflows, and observability | Active / canonical; pre-production |
| [Project-Synapse-SOC-Factory](https://github.com/Muath-Yousef/Project-Synapse-SOC-Factory) | SOC runtime: ingestion, triage, orchestration, HITL, and evidence capture | Active / canonical; pre-production |
| [kyriesoc](https://github.com/Muath-Yousef/kyriesoc) | Public SOCRoot product website; repository name retained for deployment continuity | Active public surface |
| [portfolio-site](https://github.com/Muath-Yousef/portfolio-site) | Cybersecurity engineering portfolio and delivery principles | Active portfolio |
| [Reports](https://github.com/Muath-Yousef/Reports) | Selected authorized security-assessment evidence | Reference artifact |

## Historical public artifacts

These repositories are retained to preserve design history or delivery provenance. They are not current SOCRoot implementation sources:

- [Kyrie](https://github.com/Muath-Yousef/Kyrie) — earlier CyberShield/Kyrie blueprint
- [synapse_workflow](https://github.com/Muath-Yousef/synapse_workflow) — frozen workflow visualization
- [security-workflows](https://github.com/Muath-Yousef/security-workflows) — unused placeholder superseded by the SOC runtime
- [aipmcae.com](https://github.com/Muath-Yousef/aipmcae.com) — historical website delivery artifact, separate from SOCRoot

## Private work

Some utilities, duplicate prototypes, and experimental agent research remain private. Private visibility is intentional when a repository still requires credential rotation, Git-history cleanup, client-data review, deduplication, or a safe-release decision.

Private or experimental work should not be treated as public portfolio evidence until it passes that review.

## Public-claim policy

Across these repositories:

- sensitive remediation remains human-controlled;
- SOAR dry-run is the default;
- CDN and RFC1918 ranges are not automatically blocked;
- DNS events remain notification-only;
- raw client data is not sent to external AI providers;
- production claims require documented tests, operational evidence, rollback paths, and security review.

Last reviewed: 2026-08-14.
