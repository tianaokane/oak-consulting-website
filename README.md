# Oak Consultancy — Website

Static HTML/CSS website for Oak Consultancy, hosted via GitHub Pages at [oakconsultancy.org](https://oakconsultancy.org).

---

## Pages

| File | URL | Purpose |
|------|-----|---------|
| `index.html` | / | Homepage |
| `services.html` | /services | Bid writing, strategic planning, tender management |
| `packages.html` | /packages | Pricing and package comparison |
| `about.html` | /about | Team and values |
| `contact.html` | /contact | Contact form and booking link |
| `privacy-policy.html` | /privacy-policy | Privacy policy |
| `terms-and-conditions.html` | /terms-and-conditions | Terms of use |
| `404.html` | — | Error page |
| `style.css` | — | All styles, one file |

---

## Assets

```
assets/
  favicon/
    transparent-red-favicon.png
  logo/
    horizontal-red-leaf.png
```

Keep logo and favicon filenames exactly as they are — they're referenced across every page.

---

## Making changes

The site is plain HTML and CSS — no build step, no dependencies, no CMS.

To edit content, open the relevant HTML file and change the text directly. To change colours, fonts or spacing, edit the variables at the top of `style.css` under `:root`.

If you're adding a new page, copy the structure of an existing one and update the `<title>`, `<meta name="description">` and `<h1>` tags.

---

## Deployment

Push to the `main` branch. GitHub Pages deploys automatically within a minute or two.

The custom domain is configured via the CNAME file. Don't delete it.

---

## Contact form

The contact form on `contact.html` submits to [Formspree](https://formspree.io). Responses go directly to the team's inboxes. No changes needed unless the Formspree endpoint changes.

The Microsoft Bookings link also on `contact.html` should point to the live booking page — update the `href` if the URL changes.

---

## Fonts

Loaded from Google Fonts: **DM Serif Display** (headings) and **DM Sans** (body). No local files needed.

---

## What was removed in the 2025 redesign

The following pages were consolidated and deleted:

- `who-we-help.html` → absorbed into homepage and services
- `bid-writing.html` → now part of `services.html#bid-writing`
- `strategic-planning.html` → now part of `services.html#strategic-planning`
- `tender-management.html` → now part of `services.html#tender-management`
- `faq.html` → key content absorbed into packages and contact pages
- `case-studies.html` → testimonials absorbed into homepage and about page

---

*Built and maintained by Tiana O'Kane.*
