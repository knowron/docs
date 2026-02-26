# KNOWRON Documentation

This repository contains the source for the [KNOWRON](https://knowron.com) product documentation site, built with [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

The documentation is published at **[docs.knowron.com](https://docs.knowron.com)** and is available in English and German.

## What is KNOWRON?

KNOWRON is a knowledge management platform for blue-collar workers and service organizations. It provides a single search interface for organizational knowledge — including machine documentation, troubleshooting guides, tutorials, and logbook entries — accessible on mobile (Native Assistant) and web (Control Suite).

## Repository Structure

```
docs/                   # Markdown source files
  index.en.md           # Homepage (English)
  index.de.md           # Homepage (German)
  Getting Started/      # Quickstart guides for Native Assistant and Control Suite
  Features/             # Feature documentation (search, logbook, AI reports, etc.)
  Admin Documentation/  # Admin guides (roles, permissions, security, subtenancy)
  updates/              # Product update notes
mkdocs.yml              # MkDocs configuration (nav, theme, plugins)
requirements.txt        # Python dependencies
```

## Local Development

### Prerequisites

- Python 3.x
- pip or conda

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run locally

```bash
mkdocs serve
```

The site will be available at `http://127.0.0.1:8001`.

### Build static site

```bash
mkdocs build
```

## Internationalization

Documentation is maintained in both **English** (`*.en.md`) and **German** (`*.de.md`) using the [`mkdocs-static-i18n`](https://github.com/ultrabug/mkdocs-static-i18n) plugin. The default language is English.
