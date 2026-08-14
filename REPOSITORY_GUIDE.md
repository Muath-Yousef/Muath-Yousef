# Repository Guide

This guide separates current engineering work, public product communication, academic evidence, reusable tools, and historical artifacts.

## Core ownership rule

**Project Synapse and SOCRoot are independent projects.**

- **Project Synapse** is the graduation project: an open-source cybersecurity architecture that combines security tooling with data analytics and is designed to scale.
- **SOCRoot** is a commercial innovation intended to sell automatable cybersecurity services by subscription when they provide clear, measurable customer value.
- Knowledge or code may be reused between them, but reuse does not merge scope, ownership, maturity, or success criteria.

## Maturity labels

| Label | Meaning |
|---|---|
| **Active / canonical** | Current source of truth for one documented responsibility |
| **Active documentation** | Public architecture or portfolio material; not a production implementation |
| **Pre-production** | Engineering work that still requires documented validation before production claims |
| **Historical / archived** | Retained for provenance; no longer an active product direction |
| **Private / safety review** | Kept non-public while credentials, history, client data, or release suitability are reviewed |

## Active public work

| Repository | Owner and role | Current maturity |
|---|---|---|
| [project-synapse](https://github.com/Muath-Yousef/project-synapse) | **Project Synapse:** graduation-project architecture, open-source components, data-analysis flow, evidence gates, and scalability roadmap | Active technical documentation |
| [kyriesoc](https://github.com/Muath-Yousef/kyriesoc) | **SOCRoot:** public website, service positioning, value communication, and maturity boundaries | Active public surface; pre-production |
| [portfolio-site](https://github.com/Muath-Yousef/portfolio-site) | Professional portfolio; presents Project Synapse and SOCRoot as separate tracks | Active portfolio |
| [Reports](https://github.com/Muath-Yousef/Reports) | Selected authorized security-assessment evidence | Reference artifacts |

## Active private engineering

| Repository | Owner and role | Current maturity |
|---|---|---|
| `ide-agentic-engine` | **SOCRoot candidate control plane:** portals, RBAC, client state, onboarding, evidence workflows, and observability | Active / pre-production / private safety review |
| `Project-Synapse-SOC-Factory` | **Project Synapse runtime/POC:** ingestion, triage, orchestration, HITL, and evidence capture for technical validation | Active / pre-production / private safety review |
| `security-tools` | Reusable authorized security utilities; not automatically owned by either project | Active private work |

Private visibility is deliberate. Current trees may be sanitized, but historical commits remain non-public until credential rotation, client-data review, dependency and license review, and history cleanup are complete.

## Integration rule

The SOCRoot control-plane candidate may integrate with a Project Synapse runtime component only through an explicit, tested contract. An integration is justified for SOCRoot only when it improves a service that a customer is willing to pay for; it is justified for Project Synapse only when it supports the graduation-project deliverable and evidence.

## Archived public artifacts

These repositories preserve design history or delivery provenance and are not current implementation sources:

- [Kyrie](https://github.com/Muath-Yousef/Kyrie) — earlier CyberShield/Kyrie blueprint.
- [synapse_workflow](https://github.com/Muath-Yousef/synapse_workflow) — frozen Project Synapse workflow visualization.
- [security-workflows](https://github.com/Muath-Yousef/security-workflows) — unused placeholder.
- [aipmcae.com](https://github.com/Muath-Yousef/aipmcae.com) — historical website delivery artifact, separate from both Project Synapse and SOCRoot.

## Archived private safety-review work

- `cyber_framework` — superseded SOC-automation prototype retained for controlled comparison.
- `id-exposure-scanner` — duplicate scanner prototype pending a safe-release decision.
- `socroot-node1` — frozen SOCRoot agent experiment; production use is prohibited.
- `socroot-demo-client` — quarantined SOCRoot client-delivery artifact.

Private or experimental work is not public portfolio evidence and must not be reactivated or republished before the documented review gates are satisfied.

## Public-claim policy

Across these repositories:

- evidence is separated from aspiration;
- sensitive remediation remains human-controlled;
- SOAR dry-run is the default;
- CDN and RFC1918 ranges are not automatically blocked;
- DNS events remain notification-only;
- raw client data is not sent to external AI providers;
- production claims require documented tests, operational evidence, rollback paths, and security review;
- Project Synapse metrics do not prove SOCRoot customer value;
- SOCRoot revenue does not by itself validate the academic deliverable.

Last reviewed: 2026-08-14.
