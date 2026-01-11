# Fix “tasks not visible to teammates” (permissions)

**Applies to:** End users, Workspace admins  
**Last updated:** 2026-01-04

## Overview
If you created tasks but your teammates can’t see them, the issue is usually related to **project access**, **roles/permissions**, or **filters**.

## Symptoms
- A teammate can’t see tasks you created in a project
- A teammate sees the project but not specific tasks
- Tasks are visible to you but not to other members
- Tasks appear missing after someone joins the workspace

## Step 1: Confirm the teammate has access to the project
Tasks are visible only to users who can access the project.

1. Open the project.
2. Check the project members (or sharing settings).
3. Confirm the teammate is listed as a member/collaborator.

If they’re not included, invite them to the project/workspace.

Related:
- [Invite teammates](../getting-started/invite-team.md)

## Step 2: Check role-based permissions
If your workspace uses roles, a user’s role may limit what they can view.

- Ask a Workspace admin to confirm the teammate’s role (Admin/Member/Viewer).
- Confirm the role includes access to projects/tasks.

Related:
- [Roles and permissions](../admin/roles-and-permissions.md)

## Step 3: Rule out filters and views (common)
Sometimes tasks are “missing” because of filters.

On the teammate’s side, ask them to:
1. Clear filters (assignee, status, due date).
2. Switch views (List/Board/Calendar) and try again.
3. Search for a keyword from the task title.

Related:
- [Fix “search not returning results”](search-not-working.md)

## Step 4: Confirm the task status and location
Check that the task wasn’t moved or hidden by workflow rules.

1. Open the task and confirm:
   - Project name
   - Section/column (if using boards)
   - Status (open/closed/done)
2. If the project supports archived items, check archived/completed lists.

## Step 5 (Admins): Check workspace security/access settings
Admins should verify:
- Whether project visibility is restricted (for example, “Only admins can create private projects”).
- Whether guests/viewers have read-only or limited project access.
- Whether allowed domains or security rules affect newly invited users.

Related:
- [SSO and security settings](../admin/sso-and-security.md)

## If the issue continues
Collect the following and share with your Workspace admin or support:
- Task URL (or task title)
- Project name
- The teammate’s email/role
- Screenshot of teammate’s view (filters panel if possible)
- Approximate time the issue started (with timezone)

## Related articles
- [Roles and permissions](../admin/roles-and-permissions.md)
- [Invite teammates](../getting-started/invite-team.md)
- [Troubleshoot login issues](login-issues.md)