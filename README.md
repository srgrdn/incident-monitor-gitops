# Incident Monitor (GitOps Repo)

Репозиторий-источник истины для Argo CD.

## Структура

- `argocd/` — Application/AppProject манифесты
- `apps/incident-monitor` — kustomize база и env overlays
- `clusters/k3s-test` — cluster-specific включение приложений
