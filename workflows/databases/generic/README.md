# Generic Database Validation Workflow

This workflow provides a lightweight database health check:

- `database-health-check` looks for database-like pod names and validates healthy pod phase.

## Configuration

- `target_namespaces` (default: `default`)
- `db_name_pattern` (regex, default: `postgres|mysql|mariadb|mongo|redis|cockroach|db`)
