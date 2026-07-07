# 10 — Python for SRE

Automation-first Python interview preparation — the scripting fluency SRE/DevOps interviews actually test, not competitive-programming algorithms.

| File | Description |
|---|---|
| [`python-for-sre-interview-handbook.html`](./python-for-sre-interview-handbook.html) | "The Python for SRE Interview Handbook." A complete 20-chapter book covering fundamentals through exception handling, then the SRE-specific layer — file/log handling, JSON, OS/subprocess, the `requests` library, regex for log parsing, Kubernetes automation (`kubectl`/SDK), AWS/Azure automation (boto3/Azure SDK), a 50-question rapid-fire bank, and a portfolio chapter of six complete, production-shaped scripts (pod health checker, disk cleanup, SSL expiry checker, log analyzer, Slack notifier, daily report generator). |

**Key topics covered:** file and log parsing, exception handling for unattended scripts, JSON/API response handling, `subprocess` for shelling out to `kubectl`/`terraform`/system commands, the `requests` library (timeouts, retries, auth), regex for structured log extraction, and end-to-end automation scripts combining all of the above.

**How to use:** if you're already fluent in core Python, skim Chapters 1–8 and focus on Chapters 9–20, where SRE-specific value concentrates. Chapter 19 is a rapid-fire drill bank for the day before an interview; Chapter 20 is the portfolio chapter — scripts worth actually publishing to GitHub as evidence of applied skill, not just interview answers.

This pairs naturally with [`07-scripting-and-automation`](../07-scripting-and-automation) (which covers Python and Unix/shell as quick cheat sheets) and with [`02-kubernetes`](../02-kubernetes) / [`04-aws`](../04-aws) / [`05-azure`](../05-azure) for the automation targets these scripts actually operate on.
