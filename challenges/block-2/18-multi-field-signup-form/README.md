# Issue #18 — Build a multi-field signup form (number, date, email)

**Tier:** Intermediate (3pt)

## What to build

Build a signup form that uses the right input type for each piece of data — `number`, `date`, and `email` — with constraints that match real-world rules.

## Requirements

- `<input type="email">` for email, `required`
- `<input type="date">` for date of birth, with a `max` that prevents future dates
- `<input type="number">` for age or years of experience, with sensible `min`/`max` (and `step` if needed)
- Every input has an associated `<label>`, and the form can be completed using only the keyboard

## Where to put your work

```
challenges/block-2/18-multi-field-signup-form/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Each field uses the correct input type and constraint attributes
- PR opened against `main`, linked to this issue (`Addresses #18`)

---

See [`example/index.html`](example/index.html) for a worked reference.
