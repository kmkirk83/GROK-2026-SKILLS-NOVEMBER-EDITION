---
name: autonomous-ship-deploy
description: Autonomously build complete and ship code projects to free public platforms (Vercel primary Netlify fallback) so end users can interact with a live URL. Use when the user asks to ship to Vercel, deploy live, publish for users, autonomous deploy, full user interaction URL, or any request to take a code project from repo to a free public deployment without manual hosting steps.
---

# Autonomous Ship and Deploy

## Overview

End-to-end workflow that takes a GitHub or local code project through completion and deploys it to a free public URL for full user interaction. Primary target is Vercel Hobby free tier. Fallback is Netlify. Integrates the existing autonomy suite so build quality and release discipline are not sacrificed for speed.

## Skills this workflow orchestrates

| Skill | Role in ship pipeline |
|-------|------------------------|
| project-autonomy-bootstrap | Entry point; loads the full autonomy stack |
| task-decomposition-verifier | Verified plan with deploy as a first-class done criterion |
| product-delivery-swarm | Frontend plus backend completion, tests, docs, GitHub Release |
| autonomous-ai-build-playbook | Outcome contract, architecture, quality gates before ship |
| vibe-coding-maximizer | Fast production-minded implementation practices |
| background-completion-swarm | Finish stubs and TODOs before deploy |
| agent-eval-improver | Score readiness at pre-deploy gate |
| skill-gap-analyzer | Detect missing deploy capability and close it |

## Connected platforms

- Vercel: list_teams, create_git_project, create_deployment, create_project, create_project_env, get_project
- Netlify: create-new-project, deploy-site, manage-env-vars, project readers
- GitHub: repo link, tags, releases

Prefer Vercel git-linked projects so every push to main auto-deploys. Use Netlify when the stack is static-only or the user requests it.

## Done criteria (ship complete)

1. Working GUI frontend (or intentional API-only with documented playground)
2. Complete backend or serverless functions as required
3. Code on GitHub main (or agreed production branch)
4. Live public HTTPS URL on Vercel or Netlify
5. Env vars set for production (no secrets in git)
6. Optional: GitHub Release tag plus ship notes with the live URL

## Autonomous ship protocol

### Phase 1 - Ingest and plan

1. Accept repo URL, local path, or product goal.
2. Inventory stack (Next.js, Vite, React, static, API routes, Prisma, etc.).
3. Restate done criteria including live public URL.
4. Run task-decomposition-verifier; include deploy and smoke-check as terminal tasks.
