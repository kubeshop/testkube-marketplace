# Kubernetes Core Validation Workflows

This folder contains generic Kubernetes health checks:

- `namespace-scope-check`
- `pod-health-check`
- `statefulset-health-check`
- `k8s-resources-check`

## Common configuration

Most workflows use:

- `target_namespaces` (comma-separated namespaces, default: `default`)

## Notes

- These workflows use `kubectl` and require read permissions for the Testkube execution service account.
- `k8s-resources-check` can optionally fail when `metrics-server` is unavailable using `require_metrics_server=true`.
