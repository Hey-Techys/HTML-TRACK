# Issue #19 — Make an existing form fully keyboard-navigable

**Tier:** Intermediate (3pt)

## What to build

Take a form (your own from an earlier issue, or the starter in the example) and make sure a user can complete and submit it using only the keyboard: Tab, Shift+Tab, Space, Enter, and arrow keys.

## Requirements

- Every control is a native, focusable element (`<input>`, `<select>`, `<textarea>`, `<button>`) — no clickable `<div>`/`<span>`
- Tab order follows the visual order; no positive `tabindex` values
- Submit uses a real `<button type="submit">`
- Focus is visible on every control (don't remove the focus outline)

## Where to put your work

```
challenges/block-2/19-keyboard-navigable-form/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- You can fill in and submit the whole form with the mouse unplugged
- PR opened against `main`, linked to this issue (`Addresses #19`)

---

See [`example/index.html`](example/index.html) for a worked reference.
