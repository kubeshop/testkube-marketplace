# Persistent Volume Validation Workflow

This workflow validates PVC-to-pod attachment:

- `pv-attachment-check` ensures each PVC is mounted by at least one pod.

## Configuration

- `target_namespaces` (default: `default`)
