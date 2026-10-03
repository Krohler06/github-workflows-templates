# GitHub Actions templates

Reusable workflow templates and setup guidance for standardizing CI/CD across repositories.

## Quick start

Start with the [Quick Start guide](QUICK-START.md), which describes how to select and adopt a workflow template. Review each workflow's triggers, permissions, required secrets, and repository-specific assumptions before enabling it.

## Using a template

1. Browse the workflow templates in this repository.
2. Choose the workflow that matches the project language and required checks.
3. Copy the workflow into the target repository under `.github/workflows/`.
4. Adjust triggers, runtime versions, secrets, permissions, and project commands.
5. Commit the workflow and inspect the first run in the **Actions** tab.

Treat templates as starting points, not drop-in guarantees: validate them against the target repository and grant only the minimum permissions required.

## Contributing

Keep templates reusable, document any required secrets and assumptions, and update `QUICK-START.md` when setup steps change.
