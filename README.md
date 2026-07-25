# .github

Org-wide shared machinery for the BaseCradle fleet. Owned by the capital ([`basecradle/basecradle`](https://github.com/basecradle/basecradle)); per-repo files always override anything here.

## Contents

| Path | Purpose |
|---|---|
| `.github/workflows/needs-human-ntfy.yml` | Reusable workflow: publishes a push notification (via ntfy.sh) when the `needs-human` label is applied on a fleet repo. Each repo calls it from a small stub workflow. |

Community-health defaults (a public `SECURITY.md`, the org profile README, workflow templates) may land here later.
