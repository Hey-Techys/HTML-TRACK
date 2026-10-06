# Issue #15 — Build a booking form with validation, an ARIA live region, and full SEO meta tags

**Tier:** Advanced (6pt)

## What to build

Build an appointment booking form that combines native validation attributes across several field types, includes a visually-hidden `aria-live` status region (markup only — no JavaScript required), and ships on a page with a complete SEO meta tag set.

## Requirements

- Date input (`type="date"`) with `required`, constrained with `min` to disallow past dates
- Phone input (`type="tel"`) with a `pattern` and `placeholder` showing the expected format
- Email input (`type="email"`) with `required`
- A visually-hidden element with `aria-live="polite"` reserved for a future confirmation message
- Page `<head>` includes `<title>`, `<meta name="description">`, and `<meta name="viewport">`

## Where to put your work

```
challenges/block-2/15-booking-form-aria-live/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Date, phone, and email fields all enforce their constraints natively
- PR opened against `main`, linked to this issue (`Addresses #15`)

---

See [`example/index.html`](example/index.html) for a worked reference.
