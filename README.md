# pipeline-pilot

Sandbox for the Synergaise gated client-build pipeline (Phase 1).

Caesar opens PRs against `main`; CI (incl. a mandatory gitleaks secret-scan) must pass;
a human performs the merge. Caesar can never push to `main` or merge — enforced by branch
protection and an MCP `merge_pull_request` deny.

<!-- test-pr: gated pipeline smoke test -->
