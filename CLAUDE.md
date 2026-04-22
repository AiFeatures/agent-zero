# agent-zero — Claude Code Context

## Overview

- **Repository**: AiFeatures/agent-zero
- **Enterprise**: iAiFy
- **Language**: Python
- **Upstream**: https://github.com/agent0ai/agent-zero
- **Description**: General-purpose autonomous AI agent framework (iAiFy fork)

## Fork relationship

iAiFy fork of `agent0ai/agent-zero`. Upstream merges run on a monthly/quarterly
schedule per `Ai-road-4-You/governance/docs/runbooks/fork-upstream-merge.md`.
We never push back to upstream.

On upstream merge: **always preserve** the iAiFy overlay files
(`CLAUDE.md`, `AGENTS.md`, `.github/workflows/iaify-*.yml`,
`.github/dependabot.yml`, `.github/copilot-instructions.md`).

## Conventions

- Conventional commits: `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, `test:`
- Kebab-case filenames for new files
- Branch protection on main — PRs required
- CODEOWNERS: @ashsolei

## Shared resources

| Asset | Location |
|---|---|
| CI/CD workflows | `Ai-road-4-You/enterprise-ci-cd@v1` |
| Composite actions | `Ai-road-4-You/github-actions@v1` |
| Governance | `Ai-road-4-You/governance` |
| Repo templates | `Ai-road-4-You/repo-templates` |
