# Workspace Management

!!! warning "Admin-only feature"

    Only users with the **Admin** role can create and manage Workspaces. If you need a Workspace set up, contact your organization's KNOWRON admin.

Workspace Management gives you direct control over who in your organization sees what content, down to the individual machine. No waiting on KNOWRON, no back-and-forth with support. You set it up, you manage it.

## What is a Workspace?

A Workspace defines a curated view of KNOWRON for a specific team or audience. Think of it as giving different groups their own tailored experience: your sales team sees what they need, your technicians see what they need, and content does not bleed between them.

<p align="center"><img src="https://i.imgur.com/XI3ULBw.png" width="100%"></p>

!!! note "Workspaces and Client Spaces are separate"

    Workspaces and [Client Spaces](../Admin%20Documentation/subtenancy.en.md) are distinct features and do not interact. Client Space users do not have access to Workspaces.

## Special Workspaces

Every organization has two special Workspaces that can be configured independently or set to the same Workspace.

### Global Workspace

The Global Workspace contains all products, no matter what. Every product in your organization is always visible here. This ensures that no product is ever "orphaned" without a Workspace, which would break core product functionality.

### Default Workspace

The Default Workspace is the Workspace new users are automatically assigned to when they join your organization.

!!! tip "Just getting started?"

    If you have not set up any Workspaces yet, the Global Workspace and the Default Workspace are the same Workspace, and it is the only Workspace. You do not need to configure anything to get started.

## How are new products assigned to Workspaces?

When a user creates a new product, it is always added to the **Global Workspace** automatically. The user is then asked which additional Workspace they want to assign the product to, based on the Workspaces they belong to.

This means every product always has a home, and users stay in control of where new content ends up.

## Where to find it

Navigate to **Settings -> Workspace Management** in the Control Suite.

<p align="center"><img src="PLACEHOLDER_SCREENSHOT" width="100%"></p>

## What can you do?

### Create and manage Workspaces

From the Workspace Management screen you can create new Workspaces and view all existing ones at a glance, including their status and expiry dates.

### Control content visibility

A dedicated **Workspace Administration** page lets you define exactly which products and machines are visible in each Workspace. Visibility changes require an explicit action from an admin, so content never leaks accidentally.

## Related pages

- [Client Spaces](../Admin%20Documentation/subtenancy.en.md)
- [Roles and Permissions](../Admin%20Documentation/Security%20and%20Access/roles_and_permissions.en.md)
- [Product Access Groups](../Admin%20Documentation/Security%20and%20Access/product_access_groups.en.md)
