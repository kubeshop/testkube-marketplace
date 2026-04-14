# Ingress Validation Workflow

This workflow validates basic ingress health:

- `ingress-health-check` verifies that ingress backends reference services with ready endpoints.

## Configuration

- `target_namespaces` (default: `default`)
