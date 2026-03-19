# Single Sign-On (SSO)

!!! info "KNOWRON Add-on"
    Single Sign-On is available as an add-on service for all KNOWRON package tiers. [Contact our sales team](mailto:sales@knowron.com) to get started.

Single Sign-On lets your workforce log into KNOWRON using the same corporate credentials they already use for other company tools. Instead of managing a separate KNOWRON password, users authenticate through your organization's identity provider (IdP) — and KNOWRON lets them in automatically.

**Why organizations enable SSO:**

- **One login for everything** — users access KNOWRON alongside their other tools with no extra credentials
- **Stronger security** — fewer passwords means less phishing risk, password reuse, and credential sprawl
- **Centralized access governance** — MFA, conditional access, and user offboarding are managed from a single place (your IdP), with changes reflected in KNOWRON automatically
- **Audit trail** — authentication events flow into your existing identity logs and SIEM tooling

---

## How KNOWRON's SSO works

### User provisioning

When SSO is enabled, users authenticate through your IdP — but they still need an existing KNOWRON account to log in.

**The default is pre-provisioned accounts.** KNOWRON accounts must be created before a user's first SSO login. Your Customer Success contact can create accounts in bulk ahead of rollout. This is intentional: it ensures that people in your directory who *could* authenticate via SSO don't accidentally consume licenses they don't need.

**Just-in-time (JIT) user creation** is available on request. With JIT enabled, a KNOWRON account is created automatically the first time a user successfully authenticates — no pre-provisioning required. Contact your Customer Success contact or [support@knowron.com](mailto:support@knowron.com) to enable this.

### Roles and permissions

By default, **roles inside KNOWRON are managed independently from your IdP**. A user's groups or roles in your directory have no effect on their KNOWRON role — these are assigned manually within the KNOWRON Admin Panel after the account is created.

!!! note "Coming from a tool that syncs group memberships?"
    This is a common point of surprise. KNOWRON does not automatically map IdP groups to KNOWRON roles. Role assignment remains in the hands of your KNOWRON admins unless a custom integration is arranged.

### Directory sync (SCIM)

Automated user lifecycle management via SCIM — keeping KNOWRON accounts in sync with your IdP when users join, change roles, or leave — is **not part of the standard SSO setup**. It is available on specific request. Contact [support@knowron.com](mailto:support@knowron.com) if this is a requirement.

---

## Supported identity providers

KNOWRON supports SSO with any **OIDC-compatible identity provider**, including:

- **Microsoft Entra ID** (formerly Azure Active Directory)
- **Keycloak**
- Other OIDC/OAuth2-compliant providers

SAML is also supported on request.

---

## Getting started

SSO configuration is handled end-to-end by the KNOWRON team. To get started, contact your Customer Success manager or reach out to [support@knowron.com](mailto:support@knowron.com).

Before the setup call, it helps to have the following ready:

- Your identity provider (Microsoft Entra ID, Keycloak, or another OIDC-compatible IdP)
- Whether you want pre-provisioned accounts or JIT user creation
- A list of users or groups who should have access to KNOWRON

---

## Related

- [Roles and Permissions](Security and Access/roles_and_permissions.md) — assign and manage user roles after SSO is set up
- [Admin Panel](../Features/adminpanel.md) — user management in the Control Suite
