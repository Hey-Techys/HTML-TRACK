# Issue #20 — Fix a form with 3 accessibility issues

**Tier:** Intermediate (3pt)

## What to build

The broken form below has (at least) three accessibility problems. Copy it into your folder, find the issues, fix them, and list what you fixed in an HTML comment at the top of your file.

```html
<form>
  <p>Name</p>
  <input type="text" name="name">
  <input type="email" name="email" placeholder="Email">
  <div onclick="this.closest('form').submit()">Send</div>
</form>
```

## Requirements

- Name input gets a real `<label>` connected via `for`/`id` (a `<p>` is not a label)
- Email input gets a visible `<label>` — a placeholder is not a label
- The clickable `<div>` is replaced with a real `<button type="submit">`
- An HTML comment at the top of your file lists each issue you found and how you fixed it

## Where to put your work

```
challenges/block-2/20-fix-form-accessibility-issues/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- All three issues are fixed and documented in a comment
- PR opened against `main`, linked to this issue (`Addresses #20`)

---

See [`example/index.html`](example/index.html) for a worked reference.
