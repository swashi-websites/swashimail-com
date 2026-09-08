# swashimail.com

Minimal email-identity page for the sending domain `swashimail.com`, operated by Swashi.

- Static HTML only. No framework, no build step, no sitemap, no analytics.
- **Not for indexing:** `<meta name="robots" content="noindex…">` on the page, `X-Robots-Tag: noindex` on every response (vercel.json), AI/data crawlers refused in `robots.txt`. Search crawlers may fetch the page (so they can read the noindex); they must not index it.
- Links to swashi.io are ordinary, followable links. No redirect: this domain is not canonicalised into swashi.io.
- Deploy: Vercel project `swashimail.com` → domains `swashimail.com` and `www.swashimail.com` (www → apex redirect only).

Deploy check: 2026-09-08 (README-only commit to prove GitHub → Vercel connectivity; no page content change).
