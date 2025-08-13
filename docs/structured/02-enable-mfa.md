---
product: GatewayX
feature: MFA
doc_type: procedure
audience: admin
task: enable_mfa
prerequisite: security_mode_enabled
version: 1.0
updated_at: 2025-08-01
---

# Enable MFA (Admins)

## Prerequisites
- **Security Mode enabled** in Tenant Settings.
- Admin role assigned.

## Steps
1. Go to **Admin Console → Security → MFA**.
2. Toggle **Enable MFA**.
3. Select allowed factors (TOTP, SMS, Push).
4. Click **Save**.

## Verification
Ask a test user to sign in and complete MFA.

## Related
- [Troubleshoot MFA Errors](04-mfa-troubleshooting.md)
- [Roles & Permissions](05-roles-permissions.md)
