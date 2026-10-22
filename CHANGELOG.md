# CHANGELOG — KNOWRON Docs

This file logs every change made to the documentation by Claude Code. One entry per session or batch of related changes.

## 2026-10-22 — German terminology fixes
- `docs/Features/agentic_workflows.de.md`: kept the English feature name ("Agentic Workflows" in the title, H1 and nav; "Ein Agentic Workflow" in the first sentence), replaced "Kolleginnen und Kollegen" with "Teammitgliedern" and "Fingertipp" with "Klick"
- `docs/Features/logbook_na.de.md`: fixed the mistranslated H1 and nav label "Fahrtenbuch auf dem Handy" → "Logbuch auf dem Handy"
- Added a German glossary to `_context/style-guide.md` (Agentic Workflows kept in English, Logbuch never Fahrtenbuch, tap → Klick, Benutzer, Teammitglieder) and a pointer to it in `CLAUDE.md`

## 2026-10-22 — Disable social cards (fix failed deploy)
- Removed the Material `social` plugin from `mkdocs.yml`: mkdocs-material 8.5.11 downloads its font from a Google Fonts URL that no longer returns a zip, which broke `mkdocs gh-deploy`
- Reverted the social plugin's additions to `.github/workflows/ci.yml` (Cairo system libraries, pillow, cairosvg) and `requirements.txt`
- Kept `site_url` and `site_description`; social cards to be revisited with a mkdocs-material 9.x upgrade

## 2026-10-22 — Archive Extended Answers page
- Moved `docs/Features/extended_answers.{en,de}.md` to `_context/_archive/` (no longer relevant); content is kept but no longer published
- Removed `Features/extended_answers.md` from the Search section of the nav in `mkdocs.yml`
- Marked the page as archived in `_context/feature-inventory.md`
- No redirect added; the old `/Features/extended_answers/` URL will 404

## 2026-10-22 — Agentic Workflows: contact link
- `docs/Features/agentic_workflows.{en,de}.md`: removed the "Related pages" section; linked the closing Customer Success contact line to [support@knowron.com](mailto:support@knowron.com)

## 2026-10-22 — Update Agentic Workflows content
- `docs/Features/agentic_workflows.{en,de}.md`: removed the comparison to other AI assistants; stated the feature is included at no extra cost; reworked "How you get one" (book a meeting with Customer Success, about a week to go-live); replaced "Good to know" with a "For admins" Q&A section (viewing, changing, visibility, knowledge source, languages, expanding)

## 2026-10-22 — Create Agentic Workflows page
- Created `docs/Features/agentic_workflows.en.md` — feature page (Assistant 3.0) covering what an agentic workflow is, a worked spare-parts example with a chat mockup, what a workflow defines, use-case ideas, how clients get one via Customer Success, and visibility/integration notes
- Created `docs/Features/agentic_workflows.de.md` — full German translation
- Added `Features/agentic_workflows.md` to the nav in `mkdocs.yml` under the Search section, after `extended_answers.md`
- Added `docs/stylesheets/extra.css` (registered via `extra_css` in `mkdocs.yml`) with the `kn-chat` chat-mockup styles; uses Material theme variables so it works in light and dark mode

## 2026-07-30 — Rename Public Landing Pages → Product Passport (slug)
- Renamed `docs/Features/public_landing_pages.{en,de}.md` → `docs/Features/product_passport.{en,de}.md` (page title was already "Product Passport"); new URL slug is `/Features/product_passport/`
- Updated the nav entry in `mkdocs.yml` to `Features/product_passport.md`
- Updated cross-reference links in `content_visibility.{en,de}.md` to point at `product_passport.md`
- Removed the now-stale "kept as-is / add a redirect if renamed" migration comment from the top of both pages
- No redirect from the old `/public_landing_pages/` URL was added (mkdocs-redirects is not installed); the old URL will 404

## 2026-05-12 — Create Extended Answers page
- Created `docs/Features/extended_answers.en.md` — feature page covering what Extended Answers is, the decision flow (KB-first → prompt → labeled response), the two-condition activation model (client-level + per-query consent), and user preferences
- Created `docs/Features/extended_answers.de.md` — German translation
- Added `Features/extended_answers.md` to the nav in `mkdocs.yml` under the Search section, between `search.md` and `synonym_lists.md`

## 2026-03-20 — TODO-35: Create Content Extraction Pipeline page
- Created `docs/Features/extraction_pipeline.en.md` — feature page covering what the pipeline does, supported document types, limitations (no image-embedded text), and the path to expanded extraction for specialized content
- Created `docs/Features/extraction_pipeline.de.md` — German translation
- Added `Features/extraction_pipeline.md` to the nav in `mkdocs.yml` under Control Suite Features, after `documents.md`

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
