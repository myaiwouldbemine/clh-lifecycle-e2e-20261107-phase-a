# Bootstrap Plan

2026-11-07; Codex sole accountable Builder. Issue #1 in myaiwouldbemine/clh-lifecycle-e2e-20261107-phase-a only.

## Goal / WHY
Install reviewed candidate 910c6c632ea0350eec0abf870790fed9bb1a6866 from CLH in an isolated real repository. Prove protected installation and Pages; no CLH production claim.

## Scope / Implementation Plan
Copy scripts/autonomous_lifecycle.py, test_autonomous_lifecycle.py, test_on_demand.py, agent_job.py, test_agent_job.py; .github/workflows/pages.yml, docs-check.yml, governance-tests.yml and disabled issue-agent.yml/merge-and-close-pr.yml. Include source manifest. Minimal mkdocs.yml, requirements.txt, docs/index.md are synthetic scaffolding. Native rules and Pages main-only already configured/read back before merge. First PR supplies actual required checks; no unprotected seed merge. No new token, bypass, force or direct main push.

## Verification / Acceptance
Run discovery tests, strict MkDocs, actionlint, diff check; required current-head CI success and exact head/base Self-Review. Local pinned executor checks then marks Ready/merges; intentionally stops awaiting deployment. Read installed blobs/main, dispatch expected merge SHA on main, verify exact successful run and HTTPS SHA, resume archive/readback/close. Append Result, preserve full logs and all failures. No automatic issue-closing keywords. Production remains NOT RUN.

## Rollback / budgets
Stop affected operation on mismatch/permission denial; preserve open Issue/evidence. Up to 3 attempts unchanged failure, 20-minute CI/Pages bounds within parent 120-minute budget. Future tested revert PR retains safe deployment mechanism; no reset/history rewrite. Fixture rollback is separate. No repository deletion.

## Minimal permission repair

Official rules API hides bypass_actors without ruleset write access. Preserve default local full no-bypass audit; Pages explicitly checks effective native protection only. No missing field interpreted as empty. Required strict checks, threads, force/delete prevention, exact SHA and readback retained. Copy only three reviewed changed source files, test, strict build, lint and current CI. Sole Builder Codex reviews full head/base before protected merge; existing bootstrap Issue #1 remains deployment target. No new governance Issue or token. Preserve previous failed deployment. Local complete protection read before dispatch and after deploy. Resume installation then fixture/rollback under original budget conditions.
