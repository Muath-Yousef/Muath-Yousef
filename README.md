# Mu'ath Yousef

Cybersecurity Engineer working across SOC engineering, security automation, data-aware detection, and evidence-driven delivery.

I currently maintain two **independent** cybersecurity tracks:

- **[Project Synapse](https://github.com/Muath-Yousef/project-synapse)** — my graduation project: an open-source, hybrid cybersecurity architecture that combines security tooling with data analytics and is designed to scale from a constrained prototype to a distributed system.
- **[SOCRoot](https://socroot.com)** — a commercial cybersecurity innovation focused on subscription services that can be automated and deliver enough measurable customer value to justify payment and renewal.

They may reuse engineering patterns or components, but they are not the same project and they are not measured by the same outcome.

## Current focus

### Project Synapse

- document the hybrid security and data-analysis architecture;
- make ingestion, analytics, detection, case handling, and response boundaries explicit;
- validate at least one end-to-end integration with reproducible evidence;
- measure resource use, latency, failure modes, and the path to scale;
- keep academic and engineering claims tied to reviewable evidence.

### SOCRoot

- select one narrow security service with a clear customer problem;
- define the result, acceptance criteria, delivery boundary, and subscription price;
- automate repeatable work while keeping sensitive actions human-controlled;
- validate the offer with a paying customer and measure renewal, margin, and delivery cost.

## Public repository map

| Repository | Role | Maturity |
|---|---|---|
| [project-synapse](https://github.com/Muath-Yousef/project-synapse) | Graduation-project architecture, data flow, evidence gates, and scalability roadmap | Active technical documentation |
| [kyriesoc](https://github.com/Muath-Yousef/kyriesoc) | SOCRoot website and public product communication | Active public surface; pre-production |
| [portfolio-site](https://github.com/Muath-Yousef/portfolio-site) | Professional portfolio and selected engineering work | Active portfolio |
| [Reports](https://github.com/Muath-Yousef/Reports) | Authorized security-assessment evidence | Reference artifacts |

The private engineering repositories remain non-public while Git history, credentials, client-data boundaries, and release suitability are reviewed. See [REPOSITORY_GUIDE.md](REPOSITORY_GUIDE.md) for the complete ownership and maturity map.

## Selected evidence

- [DVTA Security Assessment](https://muath-yousef.github.io/Reports/) — authorized grey-box assessment of DVTA v2.0 in an isolated lab, documenting 12 confirmed findings with evidence and mitigations.
- [Project Synapse](https://github.com/Muath-Yousef/project-synapse) — hybrid SOC graduation project. Its academic report records 967 events/second sustained throughput, 15.96-second average latency, and 95.9% precision in the single-node PSM experiment; GitHub clearly labels these as report-backed while the public reproduction package is completed.
- [SOCRoot](https://socroot.com) — public product surface for the separate commercial service direction.

## Engineering principles

- Evidence before claims.
- Sensitive remediation stays human-controlled.
- SOAR dry-run is the default.
- CDN and RFC1918 ranges are never automatically blocked.
- DNS events remain notification-only.
- Raw client data is not sent to external AI providers.
- Production claims require documented tests, rollback paths, and operational evidence.
- Shared code does not erase project ownership or success criteria.

## Connect

[SOCRoot](https://socroot.com) · [Portfolio](https://muath-yousef.github.io/portfolio-site/) · [LinkedIn](https://www.linkedin.com/in/muath-ysf)
