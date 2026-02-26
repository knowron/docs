# Workspace Management

!!! warning "Admin-only feature"

    Only users with the **Admin** role can create and manage Workspaces. If you need a Workspace set up, contact your organization's KNOWRON admin.

Workspace Management gives you direct control over who in your organization sees what content — down to the individual machine. No waiting on KNOWRON, no back-and-forth with support. You set it up, you manage it.

<p align="center"><img src="PLACEHOLDER_EXPLAINER_IMAGE" width="100%"></p>

## What is a Workspace?

A Workspace defines a curated view of KNOWRON for a specific team or audience. Think of it as giving different groups their own tailored experience: your sales team sees what they need, your technicians see what they need — and content doesn't bleed between them.

Workspaces build on top of [Subtenancy](../Admin%20Documentation/subtenancy.en.md): each Workspace is a subtenant that your organization administers directly.

A few key points:

- Content is **not visible by default** in any Workspace — visibility requires an explicit decision by a main tenant admin.
- Anything a Workspace creates internally stays **private** to that Workspace.
- Main tenant content marked as visible is available to the Workspaces you choose.

## Where to find it

Navigate to **⚙️ Settings → Workspace Management** in the Control Suite.

<p align="center"><img src="PLACEHOLDER_SCREENSHOT" width="100%"></p>

## What can you do?

### Create and manage Workspaces

From the Workspace Management screen you can create new Workspaces and view all existing ones at a glance — including their status and expiry dates.

### Control content visibility

A dedicated **Scope Administration** page lets you define exactly which products and machines are visible in each Workspace. Visibility changes require an explicit action from a main tenant admin, so content never leaks accidentally.

### Invite and manage users

Workspace admins can be invited directly by your organization. Once onboarded, they can invite and manage users within their own Workspace independently — no KNOWRON involvement needed.

### Monitor seat usage

The dashboard shows how many Workspace seats you have already assigned across all active Workspaces, so you always know where you stand.

## How does visibility work?

| Content owner | Visible to Workspaces? |
|---|---|
| Main tenant — explicitly shared | ✅ Yes, to the selected Workspaces |
| Main tenant — not shared | ❌ No |
| Workspace (created internally) | ❌ No (private to that Workspace only) |

!!! tip "Newly created content is hidden by default"

    When new products or documents are added — including via SharePoint sync — they are **not automatically exposed** to any Workspace. A main tenant admin must explicitly make them visible.

## Related pages

- [Subtenancy in KNOWRON](../Admin%20Documentation/subtenancy.en.md)
- [Roles and Permissions](../Admin%20Documentation/Security%20and%20Access/roles_and_permissions.en.md)
- [Product Access Groups](../Admin%20Documentation/Security%20and%20Access/product_access_groups.en.md)
