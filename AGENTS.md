# Agent Briefing: linkedin-recruiter-comment-automation

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/linkedin-recruiter-comment-automation`
- **Visibility**: `Public`
- **Default Branch**: `main`
- **Last Updated / Pushed**: 2026-09-08
- **Description**: Public-safe workflow and templates for finding recruiter-adjacent LinkedIn posts and drafting manual comments.
- **Context from README**: This repository packages a public-safe workflow for finding recruiter-adjacent LinkedIn posts and drafting short manual comments for them. The focus is public-sector recruiting lanes such as state, city, county, gov tech, government contractors, and adjacent hiring conversations where automation, an...


---

## 2. Tech Stack & Architecture
- **Primary Language / Ecosystem**: General / Multi-language
- **Key Directories**: `templates/`
- **Notable Top-Level Files**: `.gitignore`, `AGENTS.md`, `CLAUDE.md`, `DAILY_LINKEDIN_COMMENT_WORKFLOW.md`, `GEMINI.md`, `LICENSE`, `LINKEDIN_COMMENT_CONTRACT.md`, `PUBLIC_REPO_SCOPE.md`, `README.md`

---

## 3. Setup & Execution Commands
### Environment Setup & Installation
```bash
# Review repository files and install dependencies corresponding to the language/runtime.
```

### Running / Starting
```bash
# Check main entry point scripts or config files.
```

### Testing / Verification
```bash
# Run relevant unit/integration tests (e.g. pytest or npm test)
```

---

## 4. Recent Commit Activity (Where We Left Off)
The most recent commits show the latest development trajectory:
- `[b0075f6]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[34d3c84]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[2ebb850]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[6309aee]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[e7b7798]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[8a7f23c]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[3c979db]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[b943808]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[f20ec87]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[1413863]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `main`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Multi-Computer Handoff & Git Sync Protocol
- **On Session Start**: Always run `git pull` when opening this repository on any computer to synchronize the latest changes.
- **On Task Completion**: Before ending any agent session, the agent **MUST**:
  1. Update Section 5 (Current State & Next Steps) in this `AGENTS.md` file.
  2. Stage all modifications (`git add .`).
  3. Commit with a concise conventional message (`git commit -m "feat/fix: ..."`).
  4. Push directly to GitHub (`git push`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
