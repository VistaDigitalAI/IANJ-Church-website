# IANJ — Iglesia Apostólica del Nombre de Jesucristo

The official website of **IANJ Apostolic Church**, a bilingual (English / Spanish) conservative Apostolic Pentecostal congregation in Houston, Texas.

🔗 **Live at:** https://vistadigitalai.github.io/IANJ-Church-website/

> *"Neither is there salvation in any other: for there is none other name under heaven given among men, whereby we must be saved."* — **Acts 4:12**

---

## Stack

- 100% static HTML / CSS / JavaScript (no framework)
- Zero build step — single `index.html` is the source of truth
- Hosted on GitHub Pages
- Bilingual via `data-en` / `data-es` attribute pattern with JS toggle

## Files

| File | Purpose |
|------|---------|
| `index.html` | The site itself — fully self-contained |
| `404.html` | Custom not-found page |
| `robots.txt` | Crawler permissions (incl. AI crawlers) |
| `sitemap.xml` | URL inventory for search engines |
| `llms.txt` | Site summary for AI search citation |
| `manifest.webmanifest` | PWA manifest for installable web app |
| `favicon.svg` | Vector favicon (the IANJ mark) |
| `og-image.svg` | Open Graph / social-share preview image |
| `security.txt` | RFC 9116 security contact |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing (faster) |

## SEO Coverage

Implemented:
- ✅ Optimized title and meta description (location + brand + keywords)
- ✅ Open Graph + Twitter Card meta tags
- ✅ Canonical + hreflang (en / es / x-default)
- ✅ Five Schema.org JSON-LD blocks: Church, WebSite, Organization, FAQPage, Events
- ✅ robots.txt with explicit allow for major + AI crawlers
- ✅ XML sitemap with hreflang annotations
- ✅ llms.txt for AI search engine citation
- ✅ Geo meta tags (geo.region, geo.position, ICBM)
- ✅ Mobile / Apple / Microsoft tile meta
- ✅ PWA manifest with installable shortcuts

## Updating the Site

Edit `index.html`, then:

```bash
git add .
git commit -m "fix: updated service times"
git push
```

GitHub Pages auto-rebuilds in ~30–60 seconds.

## License

Content © 2026 Iglesia Apostólica del Nombre de Jesucristo.
