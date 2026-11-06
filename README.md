# SwitchBooks landing page

## Overview

Single-page marketing site for **SwitchBooks**: a done-for-you migration from QuickBooks Online or Xero into **Mercury Books**, including an optional permanent history archive.

## Purpose

Explain why Mercury Books does not import QuickBooks/Xero history, what SwitchBooks delivers in ~48 hours, and convert visitors to a free 15-minute scoping call (mailto CTAs).

## Features

- Hero + problem framing (Mercury clean cutover vs. lost history)
- Deliverables: chart of accounts, opening balances, open invoices, ExitVault archive
- 3-step process (scoping call → move → review & pay)
- Pricing cards in the page copy: Move ($499), Bundle ($599), ExitVault add-on (+$100)
- FAQ (Mercury import limits, Xero support, what access is needed)
- Trust points: QuickBooks left untouched until approval; pay after review

## Tech stack

- One static `index.html` (self-contained CSS)
- Optional preview screenshots: `preview.png`, `preview-mobile.png`
- Notes file: `removed-bookkeeper-copy.md`

## Run / deploy

```bash
python3 -m http.server 8080
# open http://localhost:8080/
```

Host the folder on any static host (Cloudflare Pages, Netlify, S3, etc.). Update the placeholder `mailto:TODO-your-email@example.com` links before going live.

## Notes

This is a landing page only — no backend or accounting integrations in the repo.
