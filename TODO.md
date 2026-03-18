# TODO — KNOWRON Docs

This file tracks documentation tasks. Update it as you work.

**Status legend:**
- `[ ]` — Not started
- `[~]` — In progress
- `[x]` — Done
- `[!]` — Blocked / needs human input

**To action a task:** reference it by ID (e.g. "do TODO-07"). To add a new task, append it at the bottom of the relevant section with the next available number.

---

## Cross-cutting (apply to all feature pages)

- [ ] **TODO-01** Add a subtle package indicator (Core / View / Connect / Add-on) near the top of every feature page — e.g. as a small admonition or inline tag — so readers and sales know at a glance what's required to access the feature | Priority: High | Affects: en, de | File(s): all `docs/Features/*.md`

---

## Structural Issues (fix before content work)

- [ ] **TODO-02** Add `Admin Documentation/documents_upload_guidelines.md` to the nav in `mkdocs.yml` | Priority: High | Affects: en, de | File(s): `mkdocs.yml`
- [ ] **TODO-03** Create English version of `Features/charts.md` (only DE exists) | Priority: High | Affects: en | File(s): `docs/Features/charts.en.md`
- [ ] **TODO-04** Review and restructure the nav to clearly separate Control Suite vs Native Assistant sections | Priority: Medium | File(s): `mkdocs.yml`
- [ ] **TODO-05** Add `what-is-knowron.md` to the nav (currently orphaned) | Priority: Medium | File(s): `mkdocs.yml`

---

## Content Gaps

- [ ] **TODO-06** Expand `Features/adminpanel.en.md` — currently very thin; missing: SSO, integrations, organization settings | Priority: High | Affects: en, de
- [ ] **TODO-07** Update `Getting Started/quick-start-guide-assistant.en.md` — review for accuracy against current app | Priority: High | Affects: en, de
- [ ] **TODO-08** Update `Getting Started/quick-start-guide-cs.en.md` — review for accuracy against current Control Suite | Priority: High | Affects: en, de
- [ ] **TODO-09** Write a packages/pricing overview page (currently only referenced vaguely in FAQs) | Priority: High | Affects: en, de
- [ ] **TODO-10** Update `faqs.en.md` — several answers reference old UI screenshots | Priority: Medium | Affects: en, de
- [ ] **TODO-11** Update `faqs.en.md` — replace vague references to "premium packages" and "enterprise package" with correct module names (KNOWRON Core / View / Connect); OCR/table parsing should reference the correct module, API mention should reference Integration Support | Priority: Medium | Affects: en, de | File(s): `docs/faqs.en.md`, `docs/faqs.de.md`
- [ ] **TODO-12** Update `Features/insights.en.md` — check if dashboard has changed since this was written | Priority: Medium | Affects: en, de
- [ ] **TODO-13** Expand `Features/workspace_management.en.md` — check current state | Priority: Medium | Affects: en, de
- [ ] **TODO-14** Write audience-specific landing pages (for sales, CS teams, end users) | Priority: Low | Affects: en

---

## Missing Feature Pages (no dedicated doc page exists)

- [ ] **TODO-15** Create page for **Dedicated Client Spaces** (Connect module) — explain how external users get their own permissioned workspace, roles, content access | Priority: High | Affects: en, de | File(s): `docs/Features/client_spaces.md` | Draft: `_context/_drafts/client_spaces.md`
- [ ] **TODO-16** Create page for **Digital Product Passport (DPP)** (View module) — explain public access, login-free use, Assistant Credits, compliance use cases | Priority: High | Affects: en, de | File(s): `docs/Features/digital_product_passport.md` | Draft: `_context/_drafts/digital_product_passport.md`
- [ ] **TODO-17** Create page for **Single Sign-On (SSO)** (Add-on) — how to configure, supported identity providers | Priority: High | Affects: en, de | File(s): `docs/Admin Documentation/sso.md` | Draft: `_context/_drafts/sso.md`
- [ ] **TODO-18** Create page for **Content Visibility Control** (Core) — how to control which users/groups can see which content | Priority: High | Affects: en, de | File(s): `docs/Features/content_visibility.md` | Draft: `_context/_drafts/content_visibility.md`
- [ ] **TODO-19** Create page for **Whitelabeling** (Add-on) — custom subdomain, branded emails, what's customizable | Priority: Medium | Affects: en, de | File(s): `docs/Features/whitelabeling.md` | Draft: `_context/_drafts/whitelabeling.md`
- [ ] **TODO-20** Create page for **(Custom) Data Integrations** (Add-on) — what integrations are available, how to request, API overview | Priority: Medium | Affects: en, de | File(s): `docs/Admin Documentation/integrations.md` | Draft: `_context/_drafts/integrations.md`
- [ ] **TODO-21** Create page for **Spare Part Ordering** (Core) — how to initiate orders from within KNOWRON | Priority: Medium | Affects: en, de | File(s): `docs/Features/sparepart_ordering.md` | Draft: `_context/_drafts/sparepart_ordering.md`
- [ ] **TODO-22** Create page for **Synonym Lists** (Core) — how to define and manage synonyms for search | Priority: Medium | Affects: en, de | File(s): `docs/Features/synonym_lists.md` | Draft: `_context/_drafts/synonym_lists.md`
- [ ] **TODO-23** Create page for **Content Release Process** (Core) — review and approval workflow before content goes live | Priority: Medium | Affects: en, de | File(s): `docs/Features/content_release.md` | Draft: `_context/_drafts/content_release.md`
- [ ] **TODO-24** Create page for **Branded App** (Add-on) — how white-labelling the Native Assistant works, App Store requirements | Priority: Medium | Affects: en, de | File(s): `docs/Features/branded_app.md` | Draft: `_context/_drafts/branded_app.md`
- [ ] **TODO-25** Create page for **Weekly Draft Summary Email** (Core) — what it is, how to configure recipients | Priority: Low | Affects: en, de | File(s): `docs/Features/weekly_summary_email.md` | Draft: `_context/_drafts/weekly_summary_email.md`
- [ ] **TODO-26** Expand `docs/Features/Articles/article_voice_capture.md` to fully cover **AI-powered hands-free knowledge capture** — currently covers voice in articles only; should cover logbook voice input too | Priority: Medium | Affects: en, de | Draft: `_context/_drafts/voice_capture.md`

---

## Updates Section

- [ ] **TODO-27** Write product update entry for any releases after v2.0.0 (early 2025) | Priority: High | File(s): `docs/updates/2025/`

---

## Cleanup & Deletion


---

## Translation Gaps

- [ ] **TODO-28** `Features/charts.de.md` exists with no English counterpart — complete TODO-03 first, then verify DE is in sync
- [ ] **TODO-29** Review all `.de.md` files after EN updates are made and flag any that are out of sync

---

## Completed

<!-- Move tasks here when done, with date and ID. Example: -->
<!-- - [x] **TODO-01** Description | Completed: 2026-03-18 -->
- [x] **TODO-30** Delete `docs/Features/language_priority_in_search.en.md` and `.de.md`; remove from `mkdocs.yml` nav | Completed: 2026-03-18
- [x] **TODO-32** Delete the entire `docs/updates/` directory and remove the Updates entry from `mkdocs.yml` nav | Completed: 2026-03-18
- [x] **TODO-33** Rename subtenancy pages to `client_spaces`; replace all "Subtenant"/"Subtenancy" references with "Client Space"/"Client Spaces" across docs and `mkdocs.yml` | Completed: 2026-03-18
- [x] **TODO-34** Delete all non-English and non-German page variants (`.es.md`, `.it.md`, `.pl.md`, `.zh.md`) | Completed: 2026-03-18
- [x] **TODO-31** Delete `docs/Admin Documentation/Security and Access/product_access_groups.en.md` and `.de.md`; remove from `mkdocs.yml` nav | Completed: 2026-03-18
