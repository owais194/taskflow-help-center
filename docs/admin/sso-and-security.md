# SSO and security settings

**Applies to:** Workspace admins  
**Last updated:** 2026-01-03

## Overview
Security settings help protect your workspace, including SSO (if available), 2FA requirements, and session controls.

## Configure security settings
1. Go to `Settings > Workspace settings`.
2. Select **Security**.
3. Configure the options available in your plan, such as:
   - Require 2FA
   - Session timeout
   - Allowed email domains
4. Select **Save changes**.

## Set up SSO (overview)
SSO setup varies by identity provider. A typical SSO setup includes:
1. Enable SSO in TaskFlow (Admin settings).
2. Configure your identity provider (IdP) application.
3. Add the callback/redirect URL provided by TaskFlow.
4. Test sign-in with a pilot group before enforcing SSO.

## Troubleshooting
- **Users can’t sign in after enabling SSO.**  
  Confirm email addresses match between TaskFlow and the IdP, and ensure SSO is not enforced before testing.

## Related articles
- [Troubleshoot login issues](../troubleshooting/login-issues.md)