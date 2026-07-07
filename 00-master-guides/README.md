# 00 — Master Guides

Broad, cross-topic flagship references that intentionally span multiple technology areas rather than fitting neatly into one folder. Start here for a wide, single-file view before drilling into the topic-specific folders.

| File | Description |
|---|---|
| [`sre-and-devops-complete-architect-guide.html`](./sre-and-devops-complete-architect-guide.html) | **The flagship guide.** "SRE and DevOps - Complete Architect Guide" — a large, tabbed interactive reference (42 tabs, ~130+ questions) spanning SRE fundamentals, Kubernetes, cloud, monitoring, CI/CD, and scripting in one searchable document. |
| [`devops-sre-interview-master-guide.html`](./devops-sre-interview-master-guide.html) | Cross-cutting interview guide covering Docker (fundamentals, images/layers, Dockerfile best practices, networking/storage, Compose/security), GitHub Actions, Jenkins, AWS (IAM, VPC, compute, storage/databases, observability), Azure (identity, compute/networking/AKS), and Prometheus/Grafana (architecture, PromQL, alerting). |
| [`senior-sre-interview-cheatsheet-k8s-observability.html`](./senior-sre-interview-cheatsheet-k8s-observability.html) | Condensed "Senior SRE Interview Cheat Sheet" focused on the Kubernetes + Observability intersection — good for a fast pre-interview refresh across both topics at once. |

**Why these live here instead of a topic folder:** each of these deliberately mixes multiple technology areas in one file (e.g. Docker + AWS + Azure + Prometheus in a single guide). Splitting them up would break their internal navigation and cross-references, so they're kept whole and surfaced here as flagship, browse-first resources. For deep-dives on any single topic they touch, use the corresponding numbered folder (`02-kubernetes`, `04-aws`, `05-azure`, `03-monitoring-observability`, `06-cicd-automation`).

**How to use:** if you only have time to study from one file, `sre-and-devops-complete-architect-guide.html` is the broadest single resource in this repo. Use the other two for a faster, narrower refresh closer to interview day.
