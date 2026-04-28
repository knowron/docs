# Content Visibility Control

When you publish a document, article, or tutorial in KNOWRON, you decide who can see it. Content Visibility Control lets you set this on a per-content basis — directly inside the editor — and KNOWRON enforces that choice consistently across both the Control Suite and the Native Assistant.

The central question is simple: **who should be able to see this content?** Every piece of content has exactly one visibility level, chosen from three options.

<p align="center"><img src="https://i.imgur.com/1ETa9nL.png" width="80%"></p>

---

## The three visibility levels

| Level | Who can see it |
|---|---|
| **Public** | Anyone with the link or QR code — no login required |
| **Clients** | Authenticated external users in a Client Space |
| **Internal** | Authenticated employees of your organization |

The levels are **additive**: Internal content is always visible to your employees regardless of which other tiers are active. Adding the Public or Clients tier does not force all your content to be public or client-accessible — editors choose the visibility level for each piece of content individually.

---

## Setting visibility in the Control Suite

When creating or editing a document, article, or tutorial, you will find a visibility dropdown in the editor. Select the level that matches the intended audience for that piece of content.

<p align="center"><img src="https://i.imgur.com/pNhU8xs.png" width="40%"></p>

The selected visibility applies consistently across both products:

- **Public** content surfaces on public-facing landing pages, accessible via QR code with no login required.
- **Clients** content is accessible to external users logged into a Client Space.
- **Internal** content is only visible to employees logged into the Control Suite or the Native Assistant with a valid internal account.

---

## Controlling internal visibility with Workspace Management

Content Visibility Control determines **who outside your organization** can see content. To control **who inside your organization** sees what, KNOWRON uses **Workspace Management**.

Workspaces let you organize users and content into groups that mirror your company's structure — by department, region, product line, or team. A piece of content assigned to a workspace is only visible to members of that workspace. This works alongside visibility levels: a document can be Internal (employees only) and also scoped to a specific workspace within that group.

→ See [Workspace Management](workspace_management.md) for a full walkthrough.

---

## Related

- [Workspace Management](workspace_management.md) — control which employees see which content, by team or department
- [Public Landing Pages](public_landing_pages.md) — how Public visibility works in practice, including QR codes
- [Client Spaces](../Admin%20Documentation/client_spaces.md) — give external customers their own authenticated workspace
- [Admin Panel](adminpanel.md) — manage user roles and organization-wide access
