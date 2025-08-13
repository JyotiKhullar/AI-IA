---
product: GatewayX
feature: SSO
doc_type: procedure
audience: admin
task: configure_sso
prerequisite: admin_role
version: 1.0
updated_at: 2025-08-01
---

# Configure Single Sign-On (SSO)

## Prerequisites
- **Admin** role
- Identity Provider (IdP) metadata (XML)
- Test user account at IdP

## Steps
1. Go to **Admin Console → Security → SSO**.
2. Upload **IdP metadata XML**.
3. Map attributes: `email`, `first_name`, `last_name`, `groups`.
4. Download **SP metadata** and complete configuration at IdP.
5. Click **Save** and test.

## Related
- [Roles & Permissions](05-roles-permissions.md)
