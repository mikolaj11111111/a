# QRVISION Board Prototype

A disposable Jira-style Kanban prototype in `mikolaj11111111/a`. All sample issues are fictional; they are not a QRVISION delivery backlog.

**[Open the board](https://github.com/users/mikolaj11111111/projects/2)** · [Repository Projects](https://github.com/mikolaj11111111/a/projects) · [Sample issues](https://github.com/mikolaj11111111/a/issues?q=is%3Aissue+label%3Aprototype)

## Workflow

| Column | Meaning |
| --- | --- |
| Backlog | Captured idea awaiting prioritization. |
| Ready | Clear task ready to be picked up. |
| In Progress | Work is underway. |
| Review | Implementation awaits review and acceptance. |
| Done | Accepted work; close the issue as completed. |

Drag a card between columns to change its project status. Close an accepted issue to move it to Done automatically. Reopened issues must be moved back to Ready manually. A blocked task keeps its current status and receives the `blocked` label.

## Ownership and priorities

- Use the native GitHub Assignees field for the primary owner and `@username` mentions for discussion.
- The sample Backlog task is unassigned; other samples belong to `mikolaj11111111`.
- Priority: P0 Critical, P1 High, P2 Normal, P3 Low. Set priority during triage.
- Labels: `bug`, `enhancement`, `task`, `blocked`, and `prototype`.

## Views

- **Board:** all repository issues, grouped by status.
- **Backlog:** open Backlog issues, sorted by priority.
- **My Work:** open issues assigned to the signed-in user (`assignee:@me`).
- **Blocked:** open issues with the `blocked` label.

The project is private even though this repository and its fictional issues are public. Project access is separate from repository access. No additional collaborators are invited for this prototype.

## Automation and review

Open issues from this repository are automatically added to the project. Newly added items start in Backlog, and closing an issue moves it to Done. GitHub's default **Auto-close issue**, **Pull request linked to issue**, and **Pull request merged** workflows currently remain enabled. Disabling these extra defaults to keep other transitions manual is pending confirmation.

Try moving cards, changing priority, checking My Work, and viewing the blocked sample. The six examples cover every column. QRVISION itself remains unchanged until this prototype is approved.
