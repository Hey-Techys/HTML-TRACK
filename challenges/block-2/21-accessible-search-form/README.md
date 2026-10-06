# Issue #21 — Build an accessible search form with a visually-hidden label

**Tier:** Beginner (1pt)

## What to build

Build a small search form using `role="search"` where the label is still present in the HTML for screen readers, even though it's visually hidden.

## Requirements

- Form or wrapping element uses `role="search"`
- `<input type="search">` has a real `<label>` associated via `for`/`id`
- Label is visually hidden using CSS (not `display: none`, which also hides it from screen readers) — an inline `style` using clip/position technique is acceptable
- A visible submit button is present

## Where to put your work

```
challenges/block-2/21-accessible-search-form/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- A visible submit button is present
- PR opened against `main`, linked to this issue (`Addresses #21`)

---

See [`example/index.html`](example/index.html) for a worked reference.
