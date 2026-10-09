# Issue #17 — Add the viewport meta tag to a page missing it

**Tier:** Beginner (1pt)

## What to build

Take a simple page that has no viewport meta tag and add one so it scales correctly on mobile devices. Compare the page in your browser's mobile view before and after.

## Requirements

- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` inside `<head>`
- `<meta charset="UTF-8">` is the first element in `<head>`
- Page has a `<title>` and `lang` attribute on `<html>`
- Do not disable zooming (no `user-scalable=no` or `maximum-scale=1`)

## Where to put your work

```
challenges/block-2/17-viewport-meta-tag/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Page renders at device width in the browser's mobile/responsive view
- PR opened against `main`, linked to this issue (`Addresses #17`)

---

See [`example/index.html`](example/index.html) for a worked reference.
