# Client Spaces in KNOWRON

## What are Client Spaces?
Client Spaces let our primary customers (**Main Tenants**) give branded, self-service access to their own customers (**Client Spaces**) while keeping sensitive data protected. With Client Spaces, clients can **white-label** KNOWRON, resell it, or simply invite end-customers into a controlled workspace—all without extra IT overhead.

<p align="center"><img src="https://i.imgur.com/FJn7Ei0.png" width="100%"></p>
<p align="center"><em>Whitelabeled solution for Acme GmbH (main tenant), which has given Client AG (client space) access to their own instance, where both Acme GmbH and Client AG machines are available.</em></p>

Client Spaces receive **full access to all KNOWRON features** for their own products and machines, while maintaining restricted read-only rights to the content their main tenants have decided should be visible.

Specifically, Client Spaces enable:

- **Self-Service:** Client Spaces resolve routine issues with Public docs, slashing support tickets.

- **Data Sovereignty:** Anything a Client Space creates is automatically private to that Client Space.

- **Effortless Scaling:** Main Tenants can onboard dozens of customers without complex setups.

| Actor | What it means in KNOWRON |
|-------|--------------------------|
| **Main Tenant** | Your organisation. You own the data and decide what's Public vs. Private. |
| **Client Space** | Your customer. Works in its own secure space but sees your data marked as **Public**. |
| **User** | An individual account under either a Main Tenant or a Client Space. |

``` mermaid
%% KNOWRON Tenant Hierarchy
graph TD;
    MainTenant["Main Tenant (Acme GmbH)"];
    MainUser["Main-Tenant User (Acme Employee)"];
    SubA["Client Space A ('Client AG')"];
    SubB["Client Space B ('Other Client UG')"];
    UserA1["User A-1 ('Client AG' employee)"];
    UserA2["User A-2 ('Client AG' employee)"];
    UserB1["User B-1 ('Other Client UG' employee)"];

    MainTenant --> MainUser;
    MainTenant --> SubA;
    MainTenant --> SubB;
    SubA --> UserA1;
    SubA --> UserA2;
    SubB --> UserB1;
```

### Practical Example

1. **Main Tenant** 'Acme GmbH' uploads the "Placement Machine X Maintenance Manual" to their product "Placement Machine X" and marks it as **Public**.
2. **Client Space** 'Client AG', who has bought a Placement Machine X, receives client space access for self-service. The manual appears in its KNOWRON knowledge base (whitelabeled), under the appropriate product.
3. **Client Space** 'Client AG' asks a support question to the system; the AI assistant answers from the manual and other public sources.
4. Documents marked as **Private** such as internal repair procedures stay visible only to the Main Tenant.


### Who can do what?
| Capability | Main Tenant | Client Space |
|------------|-------------|--------------|
| Create, edit or delete products | ✅ | ✅ |
| Create, edit or delete machines | ✅ | ✅ (under own *or* Main-Tenant products) |
| Create, edit or delete production lines | ✅ | ✅ |
| Create, edit or delete articles, tutorials or logbook entries | ✅ | ✅ (only under own products) |
| Upload, edit or delete documentation | ✅ | ✅ |
| Toggle Public / Private | ✅ | ❌ (everything is implicitly private) |
| Invite other users to the platform (only to their clients) | ✅ | ✅ |

### How does visibility work?
| Owner | Visibility Flag | Visible To |
|-------|-----------------|------------|
| Main Tenant | **Public** | Main Tenant **+ all its Client Spaces** |
| Main Tenant | **Private** | Main Tenant only |
| Client Space | *(implicit)* Private | That Client Space only |

---

Client Spaces in KNOWRON give you the perfect balance: you stay in control, your customers stay empowered, and everyone wins. Ready to unlock Client Spaces? **Contact our Sales team today.**
