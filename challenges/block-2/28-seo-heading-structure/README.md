# Issue #28 — Fix a page's heading structure and meta tags for SEO

**Tier:** Intermediate (3pt)

## What to build

Take a page with content and organize it with a correct, single `<h1>` heading hierarchy (no skipped levels), plus a full set of SEO meta tags in the head.

## Requirements

- Exactly one `<h1>` per page
- Heading levels increase in order with no skipped levels (e.g. no `<h2>` straight to `<h4>`)
- `<head>` includes `<title>`, `<meta name="description">`, and `<meta name="viewport">`
- Content under each heading is relevant to that heading

## Where to put your work

```
challenges/block-2/28-seo-heading-structure/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Content under each heading is relevant to that heading
- PR opened against `main`, linked to this issue (`Addresses #28`)

---

See [`example/index.html`](example/index.html) for a worked reference.
