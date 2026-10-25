# Hussain Ahmad | Portfolio

Personal portfolio for Hussain Ahmad, Senior Shopify Developer and founder of HSNLOGIX. Built to link from Upwork, LinkedIn, proposals and resume.

Static HTML/CSS/JS, no build step. Hosted on Vercel (auto-deploys from GitHub). Shares the HSNLOGIX brand system (Manrope, Inter, Bebas Neue, lime `#82FF1F`). Layout is the same template as the Ayesha Shaheen portfolio.

## Structure

```
index.html              All sections (hero, stats, about, services, portfolio, experience, reviews, contact)
assets/css/style.css    Styles. Brand tokens live in :root at the top
assets/js/main.js       Mobile nav, scroll effects, stat counters, portfolio filter, contact form
assets/fonts/           Self-hosted Manrope, Inter, Bebas Neue (same files as hsnlogix.com)
assets/img/             Profile photo, project screenshots, review avatars, og-image.png
favicon.svg
```

## Content

Real content (from hsnlogix.com): profile photo, 4 case-study projects with live links and screenshots, 7 Upwork reviews, Upwork profile link, business email.

Still to fill in:
- [ ] **LinkedIn**: replace `your-handle` in the contact links and JSON-LD `sameAs`
- [ ] **Experience dates**: confirm "2019 to Present" for Upwork and add the HSNLOGIX start year
- [ ] **Contact form**: create a free form at https://formspree.io, then replace `YOUR_FORM_ID`
- [ ] **Domain**: if a custom domain is added in Vercel, update `canonical`, `og:url`, `og:image` and JSON-LD `url`

## Branches

- `staging`: Vercel preview deploy, check changes here first
- `main`: production on Vercel (every push deploys)
