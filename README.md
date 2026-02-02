# artifact-promotion-deployment
GitOps deployment repo (Helm + environment overrides).

- charts/ : Helm chart (optional; remove if chart is elsewhere)
- apps/   : env-specific app definitions + values
- clusters/: bootstrap root apps per cluster/env
- projects/: Argo CD AppProject guardrails
