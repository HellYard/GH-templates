# 🌐 Full-Stack Project Labels Guide

This markdown document defines and organizes the labels used in this repository. Labels help triage, filter, and communicate the purpose and status of issues and pull requests.

---

## 🎯 Scope Labels

| Label Name              | Description                                 | Example                            |
|--------------------------|---------------------------------------------|------------------------------------|
| `scope: frontend`        | Client-side UI/UX                          | Styling login form                 |
| `scope: backend`         | Server-side logic                          | Email handler                      |
| `scope: database`        | DB schema and queries                      | Normalize users table              |
| `scope: api`             | API endpoint logic                         | Create `/users` route              |
| `scope: auth`            | Authentication and access                  | Add JWT authentication             |
| `scope: devops`          | CI/CD, deployment, infrastructure          | GitHub Actions pipeline            |
| `scope: accessibility`   | Accessibility improvements (a11y)          | Add ARIA tags                      |
| `scope: docs`            | Project documentation                      | Setup guide update                 |

---

## ⚙️ Type Labels

| Label Name             | Description                              | Example                              |
|------------------------|------------------------------------------|--------------------------------------|
| `type: bug`            | A defect or error                        | Fixing null pointer on login         |
| `type: enhancement`    | Improvement to existing features         | Speeding up data processing          |
| `type: feature`        | New functionality                        | Adding new user profile endpoint     |
| `type: documentation`  | Documentation-related changes            | Updating README                      |
| `type: discussion`     | Start of a conversation or proposal      | Getting input on auth flow           |
| `type: refactor`       | Internal restructuring                   | Cleaning up utils                    |
| `type: test`           | Adding or improving tests                | Writing unit tests for API           |
| `type: performance`    | Optimizing behavior                      | Reducing load time                   |
| `type: security`       | Security updates or fixes                | Fixing access control bug            |
| `type: style`          | Styling/formatting only changes          | Applying code formatter              |

---

## 🚦 Status Labels

| Label Name               | Description                             | Example                          |
|--------------------------|-----------------------------------------|----------------------------------|
| `status: backlog`        | Not started yet                         | Feature request logged           |
| `status: in progress`    | Work is underway                        | Implementing auth flow           |
| `status: blocked`        | Work is blocked by a dependency         | Waiting on DB migration          |
| `status: needs review`   | Ready for review                        | Open PR                          |
| `status: needs testing`  | QA or manual testing required           | Validate endpoint output         |
| `status: ready to merge` | Complete and approved                   | Awaiting merge                   |
| `status: duplicate`      | Already tracked elsewhere               | Duplicate bug                    |
| `status: won't fix`      | Deliberate decision not to address      | Unsupported use-case             |
| `status: invalid`        | Not actionable or incorrect             | Misunderstood requirement        |

---

## ⏱️ Effort Labels

| Label Name           | Description                     | Example                          |
|----------------------|---------------------------------|----------------------------------|
| `effort: trivial`    | Less than 5 minutes             | Fix typo                         |
| `effort: low`        | Around 1 hour                   | Add config toggle                |
| `effort: medium`     | Few hours                       | Add login component              |
| `effort: high`       | Several hours                   | Build role-based auth            |
| `effort: very high`  | Multi-day task                  | Database migration               |
| `effort: unknown`    | Needs investigation             | Vague frontend bug               |

---

## 🔨 Work Complexity Labels

| Label Name           | Description                                   | Example                           |
|----------------------|-----------------------------------------------|-----------------------------------|
| `work: obvious`      | Straightforward or boilerplate                | Fixing a config typo              |
| `work: complicated`  | Requires domain knowledge                     | Designing API endpoints           |
| `work: complex`      | Uncertain outcomes or iterative process       | Building multi-tenant architecture|
| `work: chaotic`      | Emergency with unclear scope                  | Server crash on deploy            |
| `work: disorder`     | Poorly defined, requires clarification        | Ambiguous bug report              |

---

## 🚨 Priority Labels

| Label Name                        | Description                          | Example                          |
|----------------------------------|--------------------------------------|----------------------------------|
| `priority: must-have`            | Critical for success                 | User authentication              |
| `priority: should-have`          | High value but not critical          | Admin panel filters              |
| `priority: could-have`           | Nice to have, lower priority         | Dark mode                        |
| `priority: won't-have (this time)`| Not in scope for this cycle          | Mobile version                   |

## 📝 Usage Guidelines
- **Assign at least one `scope` and one `type` label.**
- **Use `status` labels to track progress.**
- **Use `effort`, `work`, and `priority` labels for planning and estimation.**