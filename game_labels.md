# 📛 Repository Labels Guide

This markdown document defines and organizes the labels used in this repository. Labels help triage, filter, and communicate the purpose and status of issues and pull requests.

---

## 🎯 Scope Labels

These labels describe which part of the system the issue or pull request affects.

| Label Name         | Description                                              | Example                            |
|--------------------|----------------------------------------------------------|------------------------------------|
| `scope: gameplay`  | Game mechanics and interactions                         | Adjusting stamina system           |
| `scope: graphics`  | Visual elements and effects                             | Adding glow effect                 |
| `scope: ai`        | NPC and enemy logic                                     | Improving patrol behavior          |
| `scope: audio`     | Sound effects and music                                 | Adding ambient track               |
| `scope: physics`   | Movement and forces                                     | Tuning jump physics                |
| `scope: networking`| Multiplayer sync                                        | Fixing laggy interactions          |
| `scope: ui`        | HUD and menus                                           | Designing inventory screen         |
| `scope: docs`      | Design or developer documentation                       | Updating feature specs             |

---

## ⚙️ Type Labels

These describe the nature of the change or issue.

| Label Name              | Description                                       | Example                              |
|-------------------------|---------------------------------------------------|--------------------------------------|
| `type: bug`             | A defect or error                                 | Fixing null pointer on login         |
| `type: enhancement`     | Improvement to existing features                  | Speeding up claims                   |
| `type: feature`         | New functionality                                 | Adding land borders                  |
| `type: discussion`      | Opens discussion for design/decisions             | API change proposal                  |
| `type: documentation`   | Changes to documentation                          | Updating README                      |
| `type: refactor`        | Internal restructuring                            | Cleaning up utilities                |
| `type: test`            | Adding or improving tests                         | Writing unit tests for API           |
| `type: performance`     | Behavior optimization                             | Reducing lag during teleport         |
| `type: security`        | Security improvement or patch                     | Fixing permission escalation         |
| `type: style`           | Styling/formatting only                           | Applying code formatter              |

---

## 🚦 Status Labels

These indicate the progress or disposition of an issue or pull request.

| Label Name               | Description                                       | Example                              |
|--------------------------|---------------------------------------------------|--------------------------------------|
| `status: backlog`        | Not started yet                                   | Feature request logged               |
| `status: in progress`    | Actively being worked on                          | Implementing claim preview           |
| `status: blocked`        | Work paused due to dependency                     | Waiting on Paper update              |
| `status: needs review`   | Awaiting peer or code review                      | Open pull request                    |
| `status: needs testing`  | QA or validation required                         | Manual test after merge              |
| `status: ready to merge` | Approved and complete                             | Awaiting button press                |
| `status: duplicate`      | Already tracked elsewhere                         | Same bug in another issue            |
| `status: won't fix`      | Will not be resolved intentionally                | Unsupported MC version               |
| `status: invalid`        | Not actionable or incorrect                       | Misunderstood feature                |

---

## ⏱️ Effort Labels

These help estimate the size and time required to complete the task.

| Label Name           | Description                        | Example                          |
|----------------------|------------------------------------|----------------------------------|
| `effort: trivial`    | <5 minutes                         | Typo fix                         |
| `effort: low`        | ~1 hour                            | Add config toggle                |
| `effort: medium`     | Few hours                          | Add GUI menu                     |
| `effort: high`       | Several hours                      | Rewrite claim system             |
| `effort: very high`  | Multi-day or major rework          | DB migration                     |
| `effort: unknown`    | Needs investigation                | Vague bug                        |

---

## 🔧 Work Complexity Labels

These define the nature of the work in terms of how straightforward or chaotic it is.

| Label Name           | Description                                | Example                                 |
|----------------------|--------------------------------------------|-----------------------------------------|
| `work: obvious`      | Clear, known pattern                       | Fixing a config typo                    |
| `work: complicated`  | Requires experience or domain knowledge    | Designing API endpoints                 |
| `work: complex`      | Iterative with unclear path                | Implementing new gameplay mechanic      |
| `work: chaotic`      | Urgent and unpredictable                   | Production server crash                 |
| `work: disorder`     | Vague or unclear context                   | Unclear bug report                      |

---

## 🧭 Priority Labels

These indicate how critical a change is to the project timeline or vision.

| Label Name                         | Description                          | Example                           |
|-----------------------------------|--------------------------------------|-----------------------------------|
| `priority: must-have`             | Essential to project success         | Core login system                 |
| `priority: should-have`           | Important, but not critical          | Admin panel filters               |
| `priority: could-have`            | Nice to have, if time permits        | Dark mode toggle                  |
| `priority: won't-have (this time)`| Out of scope for current cycle       | Mobile app version                |

---

## 📝 How to Use Labels

- Apply **only the most relevant labels** to keep issues focused and filtered.
- Combine `scope`, `type`, and `status` labels for full context.
- Use `effort` and `priority` to help with planning and triage.