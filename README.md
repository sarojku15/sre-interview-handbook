# SRE & Platform Engineering Interview Prep

A self-contained, offline-friendly collection of study guides, cheat sheets, and interview-prep material for **Site Reliability Engineering (SRE)**, **Platform Engineering**, and **DevOps** roles — covering Kubernetes, AWS, Azure, monitoring/observability, CI/CD, scripting, and real-world troubleshooting scenarios.

Most guides are single-file interactive HTML documents (searchable, with progress tracking and category filters) that work fully offline — just open the file in a browser, no server or internet connection required.

## 📂 Repository Structure

| Folder | Contents |
|---|---|
| [`01-sre-fundamentals/`](./01-sre-fundamentals) | Core SRE discipline: SLIs/SLOs/SLAs, error budgets, toil, incident management, and a general interview console |
| [`02-kubernetes/`](./02-kubernetes) | Kubernetes deep-dive interview books, master guide, condensed cheat sheet, and an Ingress-focused guide |
| [`03-monitoring-observability/`](./03-monitoring-observability) | Prometheus, Grafana, Splunk, Dynatrace, logging/metrics/tracing interview material |
| [`04-aws/`](./04-aws) | AWS foundations handbook chapter + AWS/Terraform interview study guide |
| [`05-azure/`](./05-azure) | Azure interview study guides (full + condensed) and an Azure-for-SRE cheat sheet |
| [`06-cicd-automation/`](./06-cicd-automation) | Jenkins, GitHub Actions, GitLab, ArgoCD, Ansible, and VDI automation interview guide |
| [`07-scripting-and-automation/`](./07-scripting-and-automation) | Python and Unix/shell scripting cheat sheets for SRE automation |
| [`08-troubleshooting-scenarios/`](./08-troubleshooting-scenarios) | Real-world, production-incident-style troubleshooting scenario bank |

## 🚀 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open any `.html` file directly in a browser (double-click, or `open file.html` / `xdg-open file.html`).
3. Markdown files (`.md`) render natively on GitHub, or open them in any editor/viewer.

No build step, no dependencies, no server needed.

## 🧭 Suggested Study Path

1. Start with **`01-sre-fundamentals`** to internalize SLIs/SLOs/error budgets — the vocabulary everything else builds on.
2. Move to **`02-kubernetes`** and **`03-monitoring-observability`** — the two most commonly tested technical areas in SRE interviews.
3. Cover your target cloud in **`04-aws`** or **`05-azure`** (or both, if the role spans multi-cloud).
4. Round out with **`06-cicd-automation`** and **`07-scripting-and-automation`**.
5. Finish with **`08-troubleshooting-scenarios`** to practice applying everything to realistic, on-call-style incidents.

## 🤝 Contributing

This is a living study resource. If you spot an error, want to add questions, or want to contribute a new topic area (e.g., Vault, Terraform-specific, Chaos Engineering, Kafka), feel free to open a pull request or issue.

## 📄 License

Released under the [MIT License](./LICENSE) — free to use, adapt, and share for personal study or with your team.
