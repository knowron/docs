# Spare Part Ordering

!!! info "Available with KNOWRON Core — external user access requires KNOWRON Connect"
    Internal users can access Spare Part Ordering with **KNOWRON Core**. If your organization uses **KNOWRON Connect**, external users in Client Spaces can also submit spare part requests for the parts made available to them. [Contact our sales team](mailto:sales@knowron.com) to learn more.

Spare Part Ordering lets your users request spare parts directly from within KNOWRON — without switching to another system. Users browse the parts already associated with a machine, add what they need to a cart, and submit a request. KNOWRON routes that request to the right person in your organization by email.

The feature is available in both the Control Suite and the Native Assistant.

---

## How it works

Submitting a spare part request follows three steps:

1. **Browse** the spare parts available for the machine you're working on
2. **Add** one or more parts to your cart
3. **Submit** the request when you're ready

<p align="center"><img src="https://i.imgur.com/ySkoAM1.png" width="80%"></p>

<p align="center"><img src="https://i.imgur.com/vwvuGBZ.png" width="40%"></p>

!!! note "Parts must be set up first"
    Spare parts need to be uploaded and associated with a product line before users can order them. See [Parts Inventory](partsinventory.md) for instructions on how to set this up.

---

## A request is not a purchase

When a user submits a spare part request, **no purchase transaction takes place**. KNOWRON generates a request and sends it as an email to a predefined recipient — nothing more.

This is intentional. Companies handle pricing, purchasing workflows, and procurement permissions in very different ways. Rather than imposing a single purchasing model, KNOWRON routes the request to the right person and lets you handle fulfillment according to your own internal procedures.

---

## What happens after submission

When a request is submitted, KNOWRON sends an email to a preconfigured recipient address. There are three ways this address can be set:

- **Admin Panel** — Admins can set and update the recipient address at any time. This applies to requests submitted by internal users.
- **Per Client Space (Connect)** — If your organization uses KNOWRON Connect, the recipient address for requests submitted by external users in a Client Space can also be configured in the Admin Panel, separately per Client Space.
- **Regional support contacts** — If regional support contact addresses have been defined together with your Customer Success team, requests can be routed to those addresses instead.

→ See [Admin Panel](adminpanel.md) to configure the recipient address.

---

## Scope of a request

Each spare part request is scoped to a **single machine or product line**. Users cannot combine parts from multiple machines into one request.

---

## What the email contains

The generated email includes:

- Who created the request
- Which machine or product line the request relates to
- Which spare parts were requested, including quantities

From there, your organization handles fulfillment according to its own procurement process.

---

## External users via Client Spaces

If your organization uses **KNOWRON Connect**, external users — such as customers or partner technicians — can also submit spare part requests through their Client Space. They only see the parts that have been explicitly made available to them, scoped to their machines. This eliminates the back-and-forth typically involved in spare part requests: no ambiguity about part numbers, machine variants, or compatibility. What the client submits is already correct.

→ See [Client Spaces](../Admin%20Documentation/client_spaces.md) for details on how external user access works.

---

## Related

- [Parts Inventory](partsinventory.md) — upload and manage spare parts before ordering can be used
- [Admin Panel](adminpanel.md) — configure the recipient email address for spare part requests
- [Client Spaces](../Admin%20Documentation/client_spaces.md) — give external users access to spare part ordering via KNOWRON Connect
- [Workspace Management](workspace_management.md) — control which users access which product lines and their associated parts
