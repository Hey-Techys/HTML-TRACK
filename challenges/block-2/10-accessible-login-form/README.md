# Issue #10 — Build an accessible login form with ARIA hint text

**Tier:** Intermediate (3pt)

## What to build

Build a login form with email and password fields. Add helper hint text for the password field, connected to the input with `aria-describedby`, so screen reader users hear the requirement.

## Requirements

- `email` input: `type="email"`, `required`, with a `<label>`
- `password` input: `type="password"`, `required`, `minlength="8"`, with a `<label>`
- A hint element (e.g. `<p id="password-hint">`) states the password requirement
- Password input references the hint via `aria-describedby="password-hint"`

## Where to put your work

```
challenges/block-2/10-accessible-login-form/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Password input references its hint text via aria-describedby
- PR opened against `main`, linked to this issue (`Addresses #10`)

---

See [`example/index.html`](example/index.html) for a worked reference.
