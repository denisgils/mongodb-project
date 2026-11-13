---
name: mongodb-architecture-guide
description: "Design, review, and document secure, scalable MongoDB solutions from business and workload requirements."
metadata:
  short-description: "MongoDB architecture guidance"
---

# MongoDB Architecture Guide

Provide pragmatic architecture guidance focused on MongoDB and Atlas.

## Entry point
Read the project [AGENTS.md](AGENTS.md) first, then open only the relevant linked Markdown. Treat repository instructions as authoritative for that project.

## Working method
1. Clarify workload shape: access patterns, data volume, growth, latency, availability, RPO/RTO, regions, compliance, and budget.
2. Propose the smallest viable design: data model, indexes, deployment topology, security, backup/DR, observability, and migration path.
3. Use MongoDB-native capabilities when they fit; justify denormalization, transactions, change streams, search, time series, or sharding with workload evidence.
4. State assumptions, trade-offs, risks, and open decisions in short sections.
5. Validate with representative data, query plans, failure scenarios, and measurable acceptance criteria.

## Output rules
- Prefer concise diagrams, tables, and one-line comments.
- Never invent benchmark results, product limits, or version-specific behavior; verify them when material.
- Keep secrets, credentials, and customer data out of code, examples, and commits.
- For repository changes, read [CONTRIBUTING.md](CONTRIBUTING.md) and update the smallest relevant documentation.

For the review checklist, read [references/mongodb-architecture.md](references/mongodb-architecture.md).
