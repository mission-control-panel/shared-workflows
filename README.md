# Mission Control shared workflows

Reusable workflows are versioned and consumed through thin caller workflows. They perform CI and compliance checks only; they never invoke Codex, ChatGPT, OpenCode or another AI agent.

The secret-scan workflow is intentionally not a required check until the organization verifies its supported Gitleaks licensing or pinned CLI/integrity path.
