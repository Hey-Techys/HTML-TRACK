# Issue #21 — Write meta tags consistently across a 3-page site

**Tier:** Advanced (6pt)

## What to build

Build a small 3-page site (e.g. Home, About, Contact) where every page has a complete, consistent `<head>`: shared tags are identical across pages, while page-specific tags are unique to each page.

## Requirements

- Three pages: `index.html`, `about.html`, `contact.html`, linked to each other with a `<nav>`
- Every page has the same `charset`, `viewport`, `lang`, and favicon `<link rel="icon">`
- Every page has a **unique** `<title>` (under 60 characters) and `<meta name="description">` (50–160 characters)
- Every page has a `<link rel="canonical">` and Open Graph tags (`og:title`, `og:description`, `og:url`) matching that page

## Where to put your work

```
challenges/block-2/21-meta-tags-three-page-site/(your-name)/index.html, about.html, contact.html
```

## Definition of done

- Builds and displays correctly in a browser
- All three pages share consistent base tags and have unique, page-specific SEO tags
- PR opened against `main`, linked to this issue (`Addresses #21`)

---

See [`example/index.html`](example/index.html) for a worked reference.
