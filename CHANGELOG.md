# CHANGELOG — KNOWRON Docs

This file logs every change made to the documentation by Claude Code. One entry per session or batch of related changes.

## 2026-03-20 — TODO-22: Create Synonym Lists page
- Created `docs/Features/synonym_lists.en.md` — feature page covering what synonym lists are, why they matter, what doesn't need to be added, and the CS-assisted setup process
- Created `docs/Features/synonym_lists.de.md` — German translation
- Added `Features/synonym_lists.md` to the nav in `mkdocs.yml` under the Search section, after `search.md`

## 2026-03-20 — TODO-21: Create Spare Part Ordering page
- Created `docs/Features/sparepart_ordering.en.md` — feature page covering how spare part ordering works (browse → cart → submit), the request-not-purchase distinction, email routing configuration (admin panel, per-Client-Space, regional contacts), request scope, and external user access via KNOWRON Connect
- Created `docs/Features/sparepart_ordering.de.md` — German translation
- Added `Features/sparepart_ordering.md` to the nav in `mkdocs.yml` under Control Suite Features, directly after `partsinventory.md`

## 2026-03-19 — TODO-18: Create Content Visibility Control page
- Created `docs/Features/content_visibility.en.md` — feature page covering the three-tier visibility model (Public / Clients / Internal), how to set visibility in the editor, module requirements (Core / View / Connect), and the distinction between external visibility control and internal Workspace Management
- Created `docs/Features/content_visibility.de.md` — German translation
- Added `Features/content_visibility.md` to the nav in `mkdocs.yml` under Control Suite Features, adjacent to Workspace Management

## 2026-03-19 — TODO-01: Add module indicators to all feature pages (EN + DE)
- Added `**Available with:** KNOWRON Core` (EN) / `**Verfügbar mit:** KNOWRON Core` (DE) after the H1 on all Core feature pages
- `public_landing_pages.en.md` and `public_landing_pages.de.md` already had the `!!! info "KNOWRON View required"` admonition — left unchanged
- Also added to `charts.de.md` (DE-only page, no EN counterpart yet)

## 2026-03-18 — TODO-16: Create Public Landing Pages page
- Created `docs/Features/public_landing_pages.en.md` — feature page covering landing page contents, three access tiers (Public/All Clients/Internal), Assistant Credits, key capabilities, and DPP/EU Machinery Regulation as a compliance use case
- Created `docs/Features/public_landing_pages.de.md` — German translation
- Added `Features/public_landing_pages.md` to the nav in `mkdocs.yml` under Control Suite Features

## 2026-03-18 — TODO-34: Delete non-EN/DE language variants
- Deleted all `.es.md`, `.it.md`, `.pl.md`, `.zh.md` files (8 files under `docs/Features/Articles/`)

## 2026-03-18 — TODO-33: Rename subtenancy to client_spaces
- Renamed `docs/Admin Documentation/subtenancy.en.md` → `client_spaces.en.md` and `.de.md` → `client_spaces.de.md`
- Replaced all "Subtenancy"/"Subtenant"/"Subtenants" with "Client Spaces"/"Client Space" throughout both files
- Updated nav in `mkdocs.yml` from `subtenancy.md` to `client_spaces.md`
- Updated links in `docs/Features/workspace_management.en.md` and `.de.md`

## 2026-03-18 — TODO-32: Delete docs/updates/ directory
- Deleted the entire `docs/updates/` directory (2022, 2023, 2024, 2025 subdirectories and all files)
- Removed the `Updates` entry from the nav in `mkdocs.yml`

## 2026-03-18 — TODO-31: Delete product_access_groups pages
- Deleted `docs/Admin Documentation/Security and Access/product_access_groups.en.md` and `.de.md`
- Removed `Admin Documentation/Security and Access/product_access_groups.md` from the nav in `mkdocs.yml`
- Moved TODO-30 and TODO-31 to Completed section in `TODO.md`

## 2026-03-18 — TODO-30: Delete language_priority_in_search pages
- Deleted `docs/Features/language_priority_in_search.en.md` and `docs/Features/language_priority_in_search.de.md`
- Removed `Features/language_priority_in_search.md` from the nav in `mkdocs.yml`

**Format:**
```
## YYYY-MM-DD — Short description
- What was changed and why
- File(s) affected
```

---

## 2026-03-18 — Initial context scaffold created

- Created `CLAUDE.md` — main briefing file for Claude Code with product overview, repo structure, MkDocs conventions, terminology, and workflow instructions
- Created `TODO.md` — task tracking file pre-populated with known structural issues and content gaps identified from reading the existing docs
- Created `CHANGELOG.md` — this file
- Created `_context/products.md` — detailed reference on Control Suite vs Native Assistant
- Created `_context/packages.md` — placeholder for pricing tiers (needs human input)
- Created `_context/audiences.md` — reference on who reads the docs and what they need
- Created `_context/style-guide.md` — tone, terminology, and MkDocs formatting rules
- Created `_context/feature-inventory.md` — master inventory of all features and their documentation status

No changes were made to any published docs files.
