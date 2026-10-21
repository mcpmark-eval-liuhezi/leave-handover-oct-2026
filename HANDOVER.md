# Parental leave handover — October 2026

**Owner:** @HeziLiu (Hezi Liu)
**Effective:** Monday
**Repository:** `mcpmark-eval-liuhezi/leave-handover-oct-2026`

This is the handover document. It goes out for review via the pull request **"Handover notes before leave"** (`handover-notes` → `main`) rather than landing directly.

---

## 1. Team rosters

### What the GitHub team lookup actually returned

The team-membership lookup for @HeziLiu returned exactly one organization and **zero teams**:

| Organization | Teams | Members |
|---|---|---|
| `mcpmark-eval-liuhezi` | *(none)* | *(none — no teams exist to have members)* |

### Plain statement

**@HeziLiu belongs to no GitHub teams.** There is no team roster to hand over and no team members to name as cover — the only organization visible to this account contains no teams at all.

### Implication for leave cover

- There are no @-mentionable team handles (e.g. `@org/team-slug`) to route work to.
- Cover must be arranged by **individual username** on each open item (see the triage section).
- If team-based cover is expected, the teams will need to be created/confirmed by someone with organization-owner permissions, because they do not exist today.

---

## 2. Notification triage

### Honest caveat

The GitHub **notifications API is not accessible to this token** (`403 Resource not accessible by personal access token` on every variant tried: default filter, participating-only, and repo-scoped). The literal notification inbox could not be read. The actionable surfaces were instead reconstructed via the GitHub search API — open PRs with @HeziLiu as requested reviewer, open issues/PRs assigned to @HeziLiu, and open issues mentioning @HeziLiu — with per-thread detail lookups on each.

### Review requests

**None.** There are zero open pull requests with @HeziLiu as requested reviewer. Nothing is blocked on a code review from you.

### Assignments and mentions that need a human before leave

**Critical-severity tracked items (highest priority):**
1. `mcpmark-eval-liuhezi/log4shell-audit#4` — Log4Shell remediation tracker (CVE-2021-44228; critical, CVSS 10.0). Related PR `log4shell-audit#3` ("Add Log4Shell audit findings") is **open, clean, and mergeable** — needs a merge decision.
2. `mcpmark-eval-liuhezi/security-tracker#3` — Track GHSA-ww5h-9m49-7xx4 (`fast-jwt`, critical, CVSS 9.8).
3. `mcpmark-eval-liuhezi/security-tracker#2` — Track GHSA-x34j-47hf-4xg7 (`tinacms` + `@tinacms/app`, critical, CVSS 9.3).
4. `mcpmark-eval-liuhezi/security-tracker#1` — Track GHSA-qx66-fv34-fjm8 (TanStack Start packages, critical, CVSS 9.3).

**Coordination / tracker items:**
5. `mcpmark-eval-liuhezi/aurora-migration#1` — Aurora Migration Master Tracker (single point of coordination).
6. `mcpmark-eval-liuhezi/academic-committee-briefing#1` — Collect semester teaching plans from department heads (follow-up from the 2026-10-21 Academic Committee meeting).
7. `mcpmark-eval-liuhezi/maintenance-backlog#5` — Repository maintenance backlog (quarter-end audit owner).
8. `mcpmark-eval-liuhezi/diabetes-trials-briefing#1` — Ship-week audit and team night plan.
9. `mcpmark-eval-liuhezi/mcp-org-diligence#1` — Diligence log (running).
10. `mcpmark-eval-liuhezi/release-prep-tracker#2` — Dependency audit (pre-release).
11. `mcpmark-eval-liuhezi/release-pipeline-notes#1` — GitHub CLI release pipeline research.
12. `mcpmark-eval-liuhezi/kg-triage-demo#1` — Epic: harden the login flow (**you are named coordinator**).
13. `mcpmark-eval-liuhezi/capacity-changes#1` — Scale checkout-loadtest to 4 replicas (**you are the recorded approver** of the scale-up).
14. `mcpmark-eval-liuhezi/meetup-planning#1` — Beijing In-Person Meetup Planning (**you are the organizer**).
15. `mcpmark-eval-liuhezi/ci-drill-sandbox-2#3` — Drill follow-up: add a CI status badge to the README.
16. `mcpmark-eval-liuhezi/lumen-tracker#2` — Set up telemetry baseline.

### What can wait until you're back

- `mcpmark-eval-liuhezi/maintenance-backlog#5` findings are already clean (no releases/PRs/TODO/workflow runs to clean).
- `mcpmark-eval-liuhezi/github-self-audit#1` — CI log cleanup follow-up: documents that there are **no** Actions runs or logs to clean; paper trail only.
- `mcpmark-eval-liuhezi/actions-audit-2026#1` — maintenance audit tracker; audit records, not live work.
- `mcpmark-eval-liuhezi/security-audit-2026#1` — advisory follow-ups log (10 Python advisories); documentation.
- `mcpmark-eval-liuhezi/url-probe-smoke-test#3` — earlier copy of the ship-week plan; superseded.
- `mcpmark-eval-liuhezi/pr-review-walkthrough-demo#2` — automated account health check; a generated report, not a request.
- `mcpmark-eval-liuhezi/infra-vendor-audit#1` — Q4 vendor sign-off: the audit already concludes "approve renewal for all three vendors."
- Any thread you are merely watching/subscribed to (unreadable today due to the API restriction) — by definition not blocking.

---

## 3. The three handover issues

| # | Title | Contents |
|---|---|---|
| #1 | Handover: team roster | The teams and members found (none — see section 1) |
| #2 | Handover: notification triage | Each notification needing a response and what to do about it |
| #3 | Handover: pull request reviews | Review status of the handover pull request |

---

## 4. Branch/PR mechanics

- **Branch:** `handover-notes`, cut from `main` (the repository's default branch).
- **Pull request:** "Handover notes before leave", `handover-notes` → `main`.
- **Default branch:** `main` also carries `ON-LEAVE.md`, a one-line pointer to the handover pull request.
- After `ON-LEAVE.md` landed, `handover-notes` was updated with the latest from `main` so the pull request merges cleanly.
