# Backflipped Studios

Public website for **Backflipped Studios LLC** — studio landing page plus per-app support, Privacy Policy, and Terms of Service pages. Hosted on GitHub Pages.

## Structure

```
index.html                       Studio landing page (lists apps + contact)
styles.css                       Shared styles
talk-about-the-day/
  index.html                     App support page
  privacy.html                   Privacy Policy
  terms.html                     Terms of Service
crypto-ta/
  index.html                     App support page
  privacy.html                   Privacy Policy
  terms.html                     Terms of Service
plan-my-plate/
  index.html                     App support page
  privacy.html                   Privacy Policy
  terms.html                     Terms of Service
color-by-numbers/
  index.html                     App support page
  privacy.html                   Privacy Policy
  terms.html                     Terms of Service
mantel/
  index.html                     App support page
  privacy.html                   Privacy Policy
  terms.html                     Terms of Use
  delete-account.html            Account deletion instructions
```

## Adding a new app

1. Copy an existing app folder (e.g. `plan-my-plate/`) to `new-app/`.
2. Update the content in `index.html`, `privacy.html`, and `terms.html` for the new app.
3. Add a card for it in the root `index.html`.

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server` from this directory.
