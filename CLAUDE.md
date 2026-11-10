# Wonder Pop | Claude Code owner instruction
## Owner authority effective 2026-11-10
Claude Code is the ONLY AI executor for code, tests, fixes, GitHub publication, TASKS.md maintenance, and independent review through a different read-only Claude agent/session. All historical Codex and ChatGPT execution/audit duties are retired. Owner decisions remain supreme.

## Master coordinator
`Sekiph82/MATCH3-MASTER-ORCHESTRATOR` assigns and prioritizes work for all eight repositories. Read its CLAUDE.md, REPOSITORIES.yaml, DEPENDENCIES.yaml and ORCHESTRATOR_RULES.md. This game's root TASKS.md remains canonical. Master coordination must link task IDs rather than duplicate or rewrite task history.

## Procedure
1. Inspect full TASKS.md and project restrictions, current remote main and actual owner-local tracked/untracked/ignored files. Fetch and reconcile safely, never overwrite owner changes or unpublished commits.
2. Accept only dependency-safe master-dispatched tasks (or fresh explicit owner override); claim work to avoid parallel collisions.
3. Implement and execute real available tests, with exact commands, environment, exit codes, original assertions, and missing-test explanations.
4. Send evidence and SHA to a **different read-only Claude reviewer**. No builder self-PASS. Update canonical TASKS.md only when actual gates are met; record blocked checks honestly.
5. Return task IDs, branch/commit, diffs, tests, reviewed evidence, blockers, upstream follow-ups and next work to Master Orchestrator.

Preserve legal/licensing/privacy and frozen acceptance, Engine ENG-M24, Level Factory LFX-M14, Visual Factory VUF-M11 gates. Do not trigger paid GitHub Actions/CI, cloud/device spending, force pushes, destructive cleanup or store/ads/IAP actions without specific owner approval. AGENTS.md is a retirement notice, not current Codex authorization.
