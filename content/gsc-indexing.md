# Unique Pools — Google Indexing (the #1 growth blocker)

> Current state (2026-07-19): site is LIVE, crawlable, fast (Mobile 92 / Desktop 100),
> valid sitemap (9 urls), GSC verify tag on all 10 pages. BUT `site:uniquepools.co`
> returns 0 — Google has NOT indexed it yet, because the Search Console property is
> not Verified + sitemap not submitted. No API workaround exists (Google retired the
> ping endpoint in 2023; Bing's is gone too). Only a human with the Google account
> can complete this.

## DO THIS (90 seconds, you only)
1. Go to **https://search.google.com/search-console/**
2. Sign in with your Google account.
3. **Add property** → "URL prefix" → paste `https://www.uniquepools.co` → Continue.
4. Verification method = **HTML tag** (already in every page's <head>). Click **Verify**.
   - If it asks for the tag, copy from any page source: `8OWAiw7qzsuKpKiXJNgkS1wKWdL1wl_xwg6UVBsQKag`
5. Left menu → **Sitemaps** → enter `sitemap.xml` → **Submit** (expect "Success", 9 discovered URLs).
6. Left menu → **URL Inspection** → paste `https://www.uniquepools.co/pool-cost-pakistan.html`
   → if "URL is not on Google" → **Request indexing**. Repeat for:
   - `https://www.uniquepools.co/`
   - `https://www.uniquepools.co/karachi-pools.html`
   - `https://www.uniquepools.co/lahore-pools.html`
   - `https://www.uniquepools.co/dubai-mep.html`

## After that
- Indexing takes **hours to ~14 days** for a new low-authority domain. Don't panic at 0 same-day.
- Re-check `site:uniquepools.co` at 24h / 48h / 7d.
- Agent (Hermes) re-runs `site:` checks on request and reports progress.

## Why this matters more than anything else
Speed, SEO tags, schema, content = DONE. None of it earns traffic until Google
indexes the pages. This is the single highest-ROI action for the week.
