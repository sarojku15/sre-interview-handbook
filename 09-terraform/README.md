# 09 — Terraform

Infrastructure as Code interview preparation, focused on the areas that actually differentiate senior candidates: state management, module design, and production troubleshooting — not just HCL syntax.

| File | Description |
|---|---|
| [`terraform-sre-interview-handbook.html`](./terraform-sre-interview-handbook.html) | "The Terraform Interview Handbook." A complete 20-chapter book covering fundamentals, HCL, providers, resources, variables, state (fundamentals, remote backends/locking, state surgery commands), modules, meta-arguments (`count` vs `for_each`), expressions/dynamic blocks, workspaces, provisioners, cloud-specific patterns (AWS/Azure/Kubernetes), CI/CD & policy-as-code, and a troubleshooting capstone with 8 full incident scenarios. |

**Key topics covered:** state management and remote backends (S3/DynamoDB, azurerm), `count` vs `for_each`, `terraform state mv`/`import`/`force-unlock`, module design and versioning, provisioners vs `user_data`/cloud-init, policy-as-code (Sentinel/OPA), drift detection, and multi-cloud provider patterns (AWS, Azure, Kubernetes/Helm).

**How to use:** if you're already comfortable with basic HCL, skim Chapters 1–7 and spend your time on Chapters 8–11 (state — where senior interviews concentrate) and Chapters 16–20 (cloud-specific patterns, CI/CD, and the troubleshooting capstone). Chapter 20's scenario bank doubles as day-before-interview rapid review.

This pairs naturally with [`04-aws`](../04-aws) and [`05-azure`](../05-azure) for cloud-specific depth, and with [`06-cicd-automation`](../06-cicd-automation) for the pipeline side of things.
