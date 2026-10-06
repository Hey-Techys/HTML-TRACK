# Issue #29 — Build a multi-section signup form with full ARIA support

**Tier:** Advanced (6pt)

## What to build

Build a signup form split into two `<fieldset>` sections — "Personal Information" and "Account Information" — with complete ARIA support: `aria-required` on every required field and `aria-describedby` linking each field to its hint or error text.

## Requirements

- Two `<fieldset>`/`<legend>` groups: Personal Information and Account Information
- Personal Information: full name, email — both `required` and `aria-required="true"`
- Account Information: username and password — both `required`, `aria-required="true"`, each with a hint `<p>` linked via `aria-describedby`
- Password field uses `minlength="8"` and its hint states the requirement
- Every input across both sections has a properly associated `<label>`

## Where to put your work

```
challenges/block-2/29-multi-section-signup-form/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- Every input across both sections has a properly associated `<label>`
- PR opened against `main`, linked to this issue (`Addresses #29`)

---

See [`example/index.html`](example/index.html) for a worked reference.
