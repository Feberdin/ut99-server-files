<!--
Purpose: Describe a small, reviewable contribution workflow.
Input/Output: A proposed change enters; tested code or documentation leaves.
Invariants: No secrets, personal data, generated build output, or unrelated changes.
Debugging: Start with the README, then reproduce CI locally and inspect the first real failure.
-->

# Contributing

1. Create a focused branch such as `codex/short-topic`.
2. Keep the change small and update documentation with behavior or configuration.
3. Never commit `.env` files, credentials, personal data, logs, or generated output.
4. Run the project-specific checks documented in `README.md`, followed by
   `git diff --check`.
5. Open a pull request that explains the change, risk, verification, and rollback.

Dependency and workflow updates must be reviewed and pass CI before merge.
Security issues belong in the private channel described in `SECURITY.md`, not
in a public issue.
