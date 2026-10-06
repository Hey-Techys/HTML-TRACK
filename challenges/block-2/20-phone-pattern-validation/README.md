# Issue #20 — Add a phone number input with `pattern` and `placeholder`

**Tier:** Beginner (1pt)

## What to build

Add a phone number field to a form that uses the `pattern` attribute to enforce a specific format, plus a `placeholder` showing the expected format.

## Requirements

- `<input type="tel">` with a `pattern` attribute enforcing a digits-and-dashes format (e.g. `[0-9]{3}-[0-9]{3}-[0-9]{4}`)
- `placeholder` attribute shows the expected format (e.g. `555-123-4567`)
- Input has an associated `<label>`
- Submitting a value that doesn't match the pattern triggers the browser's native validation message

## Where to put your work

```
challenges/block-2/20-phone-pattern-validation/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Submitting a value that doesn't match the pattern triggers the browser's native validation message
- PR opened against `main`, linked to this issue (`Addresses #20`)

---

See [`example/index.html`](example/index.html) for a worked reference.
