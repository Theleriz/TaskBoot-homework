# Software Engineering — Assignment #05

## Assignment Details
* AI-assisted repository customization, agent readiness and software risk governance.
* Choose your own small, non-sensitive software repository. The Smart Campus Booking project is NOT required.
* Work individually; use at least one AI assistant, but independently inspect, test and approve every finding.
* Submit an evidence-based audit, targeted improvements and a defensible release decision.

## Learning Outcomes
* Customize a coding agent using repository instructions and explicit operating boundaries.
* Apply one useful design pattern only when a concrete maintainability problem justifies it.
* Audit repository structure, reproducibility, tests and security for agent readiness.
* Verify AI-generated risk claims and document residual risks.

## Scenario and Starting Point
* Select a small existing project: task tracker, expense calculator, notes app, inventory tool or another approved example.
* Repository should contain working code and at least one testable behavior. Do not upload secrets or real personal data.
* Preserve a baseline commit/export, capture project structure and record `run/test/build` commands.
* Define 3-5 acceptance criteria that must remain true after changes.

---

## Tasks

### Task #01 - Baseline and context
* Create a short repository map: entry points, modules, dependencies, tests and build scripts.
* Run available tests, `lint/type` checks and build; record exact commands and actual results.
* Identify at least three concrete weaknesses or missing checks with file/command evidence.
* Distinguish observed facts from assumptions and unverified AI suggestions.

### Task #02 - Agent instructions
* Create or improve a root-level `AGENTS.md` (or `CLAUDE.md` for a compatible agent).
* Document purpose, architecture, setup, safe commands, coding conventions and test expectations.
* Specify forbidden actions: no secrets, production deployments, destructive commands or unreviewed dependency changes.
* If the tool does not automatically load the file, paste its relevant instructions explicitly and disclose this.

### Task #03 - Focused pattern decision
* Identify one maintainability problem: duplicated conditionals, mixed UI/business logic or tightly coupled dependencies.
* Evaluate a small pattern such as Strategy or Adapter; justify whether a pattern is actually necessary.
* Implement at most ONE focused refactoring, or explain why no pattern is warranted.
* Compare before/after structure and prove that acceptance criteria still hold.

### Task #04 - Read-only risk review
* Ask an AI assistant to propose risks without modifying files.
* Investigate at least FIVE candidate findings spanning at least THREE categories: correctness, maintainability, security, dependency or agent operations.
* Classify each finding as confirmed, plausible/unverified or unsupported.
* For confirmed findings, cite file paths, relevant code, command output or reproducible behavior.

### Task #05 - Risk register
* Record ID, category, cause/event/consequence, affected component and evidence.
* Score likelihood (1-3) and impact (1-3); compute `score = likelihood * impact` (1-9).
* Record mitigation, owner, verification plan and residual risk.
* Rank the top TWO confirmed risks for corrective action. Do not invent execution evidence.

### Task #06 - Agent-readiness audit
* Evaluate readable structure, README accuracy, reproducible setup and pinned dependencies.
* Check tests, lint/type checks, build commands, logging and security safeguards.
* Inspect `AGENTS.md` for permissions, safe commands, prohibited actions and review gates.
* Assign a justified readiness level: `1 Baseline`, `2 Documented` or `3 Agent-ready`; list missing evidence.

### Task #07 - Mitigation and verification
* Implement TWO minimal mitigations for confirmed risks; review each AI-proposed diff before accepting.
* Add or improve targeted automated tests when feasible; run baseline and final checks.
* Capture commands, pass/fail totals, relevant screenshots and any tests not executed.
* Update risk scores and explain remaining limitations or trade-offs.

### Task #08 - Background agent safeguards
* Design a hypothetical asynchronous agent task; actual paid background-agent access is NOT required.
* Define isolated branch/worktree, allowed files, commands, time limits and prohibited operations.
* Specify artifacts: change summary, diff, test logs, build result and risk notes.
* Require human review and approval before merge or deployment; explain failure/rollback handling.

### Task #09 - Release decision
* Choose `GO`, `CONDITIONAL` or `NO-GO` for the reviewed version.
  * **GO:** critical checks pass and no unacceptable unresolved risks remain.
  * **CONDITIONAL:** known limitations have explicit controls and owners.
  * **NO-GO:** serious risks or critical verification gaps remain.
* Support the decision using test evidence, risk register and readiness assessment.

### Task #10 - AI reflection
* Write 200-300 words: which assistant/model was used and what context it received?
* Identify one useful AI suggestion and one inaccurate, weak or unverified suggestion.
* Explain what you personally checked and how tests changed your decisions.
* Discuss whether repository instructions improved the process and what should improve next.

---

## Suggested Workflow
1. Select a repository and preserve a baseline.
2. Inspect files and execute checks.
3. Write `AGENTS.md` and define acceptance criteria.
4. Make one justified structural improvement.
5. Conduct a read-only AI risk review; challenge and score findings.
6. Mitigate two confirmed risks; rerun checks.
7. Audit readiness and decide release status.

## References
* Lesson #09 - Lecture: Customizing Your Agent and Repository.
* Lesson #09 - Practice: Apply a small number of useful patterns; `AGENTS.md` and verification.
* Lesson #10 - Lecture: Agent-Ready Codebases and Background Coding Agent Workflows.
* Lesson #10 - Practice: Review AI-assisted software for risks.

## Submission Details

### AI Assistant Indication & AI-Use Record
* Please indicate AI assistant name you have used for assignment work (e.g., ChatGPT, Gemini, Copilot, Grok, Perplexity, Claude).
* **AI-use record:** Include the tool and date, prompt summary, output used, problems found, changes made, and verification sources.

### Required Deliverables
* Repository link or source export with baseline and final version (or commit references).
* `README`, `AGENTS.md`, acceptance criteria and actual test/build output.
* Risk register (5+ evaluated findings), agent-readiness audit and two mitigation records.
* Pattern decision, background-agent safeguards, release decision and 200-300 word AI reflection.
* AI evidence appendix: `tool/model`, prompts, outputs, decisions and human verification.

### Submission Checklist
* At least FIVE risk findings across THREE categories, each classified and supported by evidence.
* TWO verified mitigations and documented residual risks.
* Readiness level `1/2/3` justified; `AGENTS.md` includes safe/forbidden actions.
* Before/after test evidence, clear `GO/CONDITIONAL/NO-GO` decision and AI-use record.
* No real credentials, confidential data or fabricated test results.

### Deadline & Policy
* **DEADLINE:** November 23, 2026 23:59:59
* Submissions that do not adhere to the required formatting guidelines will be rejected, regardless of whether the work itself is fully completed. Please note that resubmission will not be permitted if the incorrect format is used.
* Assignment work must be completed in its entirety, as the opportunity to resubmit will not be provided if it remains incomplete.