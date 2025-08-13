---
product: GatewayX
feature: MFA
doc_type: troubleshooting
audience: support
issue_code: 403
version: 1.0
updated_at: 2025-08-01
---

# Troubleshoot MFA Sign-In Failures (Error 403)

## Symptoms
- User receives **403** after entering credentials.
- MFA prompt does not appear.

## Likely Causes
- **Security Mode** not enabled (required before MFA).
- User lacks **MFA-allowed** role.
- Time drift on TOTP device > 2 minutes.

## Fix
1. Verify **Security Mode** is enabled.
2. Confirm user's role allows MFA.
3. If using TOTP, sync device time.
4. Retry sign-in.

## Related
- [Enable MFA](02-enable-mfa.md)
- [Roles & Permissions](05-roles-permissions.md)
