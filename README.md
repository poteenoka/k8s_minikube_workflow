# k8s_minikube_workflow

## CI: kubeconform

При изменении `manifests/**` или workflow — **Validate Kubernetes manifests (kubeconform)**. Утилита запускается в образе `ghcr.io/yannh/kubeconform` (`docker run` на GitHub-hosted runner). Опционально: секрет **`SLACK_WEBHOOK_URL`** — уведомление в Slack, как в `pod-status.yml`.
