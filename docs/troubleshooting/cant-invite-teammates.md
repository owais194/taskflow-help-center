# Fix “can’t invite teammates” (domain restrictions or permissions)

**Applies to:** Workspace admins, Project owners  
**Last updated:** 2026-01-04

## Overview
If you can’t invite teammates to TaskFlow, the issue is usually caused by **insufficient permissions**, **email/domain restrictions**, or **pending invites**.

## Symptoms
- You don’t see the **Invite members** button
- You get an error when sending invites
- Invites fail for certain email domains (for example, Gmail)
- The invite sends but the user can’t join the workspace

## Step 1: Confirm you have permission to invite members
In many workspaces, only Admins (and sometimes project owners) can invite new members.

1. Go to `Settings > Workspace settings > Members`.
2. Check whether **Invite members** is available.

If you don’t have access:
- Ask an Admin to invite the user, or
- Ask an Admin to update your role.

Related:
- [Roles and permissions](../admin/roles-and-permissions.md)

## Step 2: Check allowed email domains (domain restriction)
Some workspaces restrict invites to specific domains (for example, `company.com` only).

Ask an Admin to verify:
1. Go to `Settings > Workspace settings > Security`.
2. Check **Allowed email domains** (if enabled).
3. Confirm the invitee’s email domain matches the allowed list.

Related:
- [SSO and security settings](../admin/sso-and-security.md)

## Step 3: Look for a pending invite
If the user was already invited, TaskFlow may prevent duplicate invites.

1. Go to `Settings > Workspace settings > Members`.
2. Open **Pending invites**.
3. If the user is listed:
   - Select **Resend invite**, or
   - Cancel the invite and send a new one.

Related:
- [Fix “email invite not received”](email-invites-not-received.md)

## Step 4: Confirm seat limits (if applicable)
If your plan has a seat limit, you may not be able to add new members.

Ask an Admin to check:
1. Go to `Settings > Workspace settings > Billing`.
2. Review seat usage and upgrade options (if needed).

Related:
- [Billing FAQ](../faqs/billing-faq.md)

## Step 5: If your workspace uses SSO, confirm the user can authenticate
If SSO is enabled or enforced, the invitee may need:
- An account in your identity provider (IdP)
- The correct email address (must match IdP email)

Admin checks:
- Confirm SSO is configured correctly.
- Pilot test before enforcing SSO for all users.

Related:
- [SSO and security settings](../admin/sso-and-security.md)

## If the issue continues
Collect the following and share with your Admin or support:
- Inviter’s role (Admin/Member/Viewer)
- Invitee email address + domain
- Screenshot of the error message (if any)
- Approximate time the issue occurred (with timezone)

## Related articles
- [Invite teammates](../getting-started/invite-team.md)
- [Roles and permissions](../admin/roles-and-permissions.md)
- [Fix “email invite not received”](email-invites-not-received.md)
- [Billing FAQ](../faqs/billing-faq.md)