# 🌐 Elite Skill Set: AI-ASSISTANTS-ECOSYSTEM

This file defines the high-level orchestration skills for the Master Ecosystem Hub.

---

## 🏛️ Skill: Systemic Parity Enforcement
**Trigger**: When making changes that affect the architecture of the 5 specialized assistants.
**Instructions**:
1. Ensure the `README.md` format is identical across all repositories.
2. Propagate "Elite Skills" from the `ECOSYSTEM` docs to the specific assistant `SKILLS.md`.
3. Verify that `scripts/setup.sh` is functional and up-to-date in every repository.
4. Maintain the "Hybrid Tier" workflow (Plan → Execute → Verify) as the global standard.

---

## 🛡️ Skill: Global Security Audit
**Trigger**: On every commit and before any public push to GitHub.
**Instructions**:
1. Run `gitleaks detect --source . --report-format json` across all 6 repositories.
2. Ensure every repo has a standardized `SECURITY.md`.
3. Perform a "Dependency Audit" once per week to catch deprecated or vulnerable packages.
4. Block any PR that contains hardcoded credentials or unencrypted `.env` materials.

---

## 📑 Skill: Portfolio Documentation & Synthesis
**Trigger**: When summarizing the ecosystem or onboarding new users.
**Instructions**:
1. Use the `ECOSYSTEM/README.md` as the landing page for all project demonstrations.
2. Keep the "Capability Mapping" table updated with the latest 2026 features.
3. Link specialized assistant repositories to their respective sections in the hub documentation.
4. Generate a `SYSTEM_ARCHITECTURE.md` that visually maps the interactions between Claude, Cursor, and Opencode.

---

## 🔄 Skill: Cross-Repo Synchronization
**Trigger**: When a core utility script (e.g., a new MCP runner) is developed in one repo and needed in others.
**Instructions**:
1. Develop the utility in its most relevant specialized repo (e.g., a setup script in `CLAUDE`).
2. Generalize the script and move it to the `ECOSYSTEM/templates` folder.
3. Use an automated sync script to push the update to all 5 specialized assistants.
4. Version-control the "Base Template" in the `ECOSYSTEM` repository.

---

## 🕵️ Skill: Autonomous Health Auditor
**Trigger**: Scheduled maintenance or post-reflow checks.
**Instructions**:
1. Check every repo for the presence of: `README.md`, `SKILLS.md`, `scripts/setup.sh`, and `.cursorrules`.
2. Verify that all badges in active READMEs are resolving correctly.
3. Check for "Junk Files" (temporary logs, `.DS_Store`, old placeholders) and delete them.
4. Ensure the `task.md` in the current session is synced with the global project status.
