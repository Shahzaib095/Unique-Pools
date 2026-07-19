# Unique Pools & General Maintenance — Website

A static, SEO-optimised, multi-page website for **Unique Pools & General Maintenance Co.** (Karachi, est. 1989).

## Pages
- `index.html` — Home (hero, story, stats, testimonial)
- `services.html` — Services (pool construction, MEP, sauna/spa, water features, Jacuzzi)
- `portfolio.html` — Project gallery (real project photos)
- `faq.html` — FAQ with `FAQPage` schema (AI/SEO friendly)
- `contact.html` — Contact form + details
- `404.html` — Error page

## SEO / AI-readiness
- Semantic HTML5, correct heading hierarchy
- Open Graph + Twitter tags
- JSON-LD structured data on every page (Organization, Service, FAQPage, LocalBusiness)
- `sitemap.xml` + `robots.txt`
- Descriptive image `alt` text
- Floating WhatsApp lead button

## Deploy (GitHub Pages)
1. Create a repo on GitHub and push this folder to `main`:
   ```bash
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
2. In **Repo → Settings → Pages**, set Source = "GitHub Actions".
3. The site deploys automatically on every push.

|To use a custom domain, add a `CNAME` file containing your domain and update the URLs in the HTML/JSON-LD/sitemap from `uniquepools.example` to your domain. (Done: custom domain is **uniquepools.co**; `CNAME` + all URLs already updated.)

## Notes
- WhatsApp floats link to `+92 335 3477142` (Pakistan); contact block also lists UAE WA `+971 58 551 8785`. Update in all HTML `+ wa.me/` hrefs if numbers change.
- The contact form uses a Formspree placeholder in `contact.html`; set a real endpoint to receive emails, or rely on the mailto link.
