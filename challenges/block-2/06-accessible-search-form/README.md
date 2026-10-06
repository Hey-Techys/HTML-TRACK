# Issue #6 — Build an accessible search form with a visually-hidden label

**Tier:** Beginner (1pt)

## What to build

Build a small search form using `role="search"` where the label is still present in the HTML for screen readers, even though it's visually hidden.

## Requirements

- Form or wrapping element uses `role="search"`
- `<input type="search">` has a real `<label>` associated via `for`/`id`
- Label is visually hidden using CSS (not `display: none`, which also hides it from screen readers)
- A visible submit button is present

## Where to put your work

```
challenges/block-2/06-accessible-search-form/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Label is present in the HTML and readable by screen readers, even though visually hidden
- PR opened against `main`, linked to this issue (`Addresses #6`)

---

See [`example/index.html`](example/index.html) for a worked reference.
